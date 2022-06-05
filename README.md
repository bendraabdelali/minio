<h1> MinIO Python SDK for Amazon S3 Compatible Cloud Storage <h1>
  <p>MinIO Python SDK is Simple Storage Service  client to perform bucket and object operations to any Amazon S3 compatible object storage service.</p>
  <h2>Minimum Requirements</h2>
  <ul>
    <li>Python 3 or higher.</li>
    <li>Docker </li>
  </ul>
  <h2>start containers in docker </h2>
  <p>docker run  -t -d -p 
  -p 9000:9000 
  --name minio1 
  -e MINIO_ROOT_USER="abdo" 
  -e MINIO_ROOT_PASSWORD="abdo1234" 
  -v ./data:/data 
  minio/minio server /data 
  </p>
  <h2>Quick Start Example - create select insert in buckets </h2>
  This example we will  connects to an S3-compatible object storage container, make a bucket on that container, and upload a file to the bucket and delete from it.
  <a>read thee file ..</a>
  
  
  
  
