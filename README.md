<h1> MinIO Python SDK for Amazon S3 Compatible Cloud Storage <h1>
  
  <h2>Minimum Requirements</h2>
  <ul>
    <li>Python 3 or higher.</li>
    <li>Docker </li>
  </ul>
  <h2>start containers in docker </h2>
  docker run  -t -d -p \
  -p 9000:9000 \
  --name minio1 \
  -e MINIO_ROOT_USER="abdo" \
  -e MINIO_ROOT_PASSWORD="abdo1234" \
  -v ./data:/data \
  minio/minio server /data 
  
  
