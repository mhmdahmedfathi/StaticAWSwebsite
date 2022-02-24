# StaticAWSwebsite
 
### steps to Deploy static website to AWS:
<ol>
  <li>S3 Bucket</li>
  <p>First is to create S3 bucket and make the bucket any name you want</p>
  <img align="center" src="https://github.com/mhmdahmedfathi/StaticAWSwebsite/blob/main/Bucket.png" width=400/>
  </br>
  <li>Files & Folders</li>
  <p>you can upload the files needed to start static website</p>
  <img align="center" src="https://github.com/mhmdahmedfathi/StaticAWSwebsite/blob/main/StorageS3.png" width=400/>
  </br>
  <li>Policy</li>
  <p>You have to update policy of s3 object to make it allow to read from everywhare</p>
  <img align="center" src="https://github.com/mhmdahmedfathi/StaticAWSwebsite/blob/main/PolicyIam.png" width=400/>
  </br>
  <li>Configure S3 Bucket</li>
  <p>you have to make sure you allow static website hosting in order to keep in count that there are static website and enter the root file of your html here</p>
  <img align="center" src="https://github.com/mhmdahmedfathi/StaticAWSwebsite/blob/main/StaticWebsite.png" width=400/>
  </br>
  <li>Cloud Front</li>
  <p>this is optional you can view your static website for the previous step,However. this step is to make html cached so if the website is in pressure it get the page from it</p>
  <img align="center" src="https://github.com/mhmdahmedfathi/StaticAWSwebsite/blob/main/CloudFront.png" width=400/>
  </br>
  </ol>
