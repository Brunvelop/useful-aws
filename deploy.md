1. Registrar dominio (puede tardar 3 dias)

2. terraform: (se encarga de s3 y cloudfront)
    - init
    - plan
    - apply


3. SSL 
    - AWS Certificate Manager -> create certificate
    - Click certificate -> Click crear registros en Route 53

4. redirigir route 53 to cloudfront
    crear registro: (A, alias, cloudfront link)
