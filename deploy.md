1. Registrar dominio (puede tardar 3 dias)

2. terraform: (se encarga de s3 y cloudfront)
    - init
    - plan
    - apply


3. SSL 
    - AWS Certificate Manager -> create certificate
    - Click certificate -> Click crear registros en Route 53
    - (tarda un rato en aplicarse)

4. redirigir route 53 to cloudfront
    - crear registro: (A, alias, cloudfront link)

5 Cloudfront add oia
    - cloudfront, distribution, origin domain
    - select tf name, legacy, yes

6 Cloudfront add ssl
    clodfront, distribution, edit, add custom ssl and domain name

7. Usar deploy sample en la react app
    - necesario: 
        (s3) -> BUCKET_NAME
        (cloudfront)-> DISTRIBUTION_ID