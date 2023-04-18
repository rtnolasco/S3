# S3
Basic AWS Config Json Guide:

* Login to your AWS account and go to the S3 dashboard.
* Create a new bucket if you haven't already done so. To do this, click the "Create bucket" button.
* Choose a name for your bucket and select the region where you want to store your data. Click "Next".
* Configure the bucket properties as per your requirement. You can leave them as default if you want. Click "Next".
* Set the permissions for your bucket. You can leave them as default or choose to modify them as per your requirement. Click "Next".* Review your settings and click "Create bucket".
* Once the bucket is created, click on it to view its details.
* Click on the "Permissions" tab and select "Bucket Policy".

* In the Bucket Policy Editor, paste the following code to make the bucket public: **( refer to json file )

* Replace "your-bucket-name" with the actual name of your bucket.
Click "Save".



Next, you need to create an access key for your AWS account to access the S3 bucket. To do this, go to the IAM dashboard and click on "Users".

* Create a new user or select an existing one, and go to the "Security credentials" tab.
* Click "Create access key" and note down the access key ID and secret access key. These will be used to authenticate access to the S3 bucket.


