# document-search-chatbot
A chatbot that will be used to search through documents and finds the right answer based on the question you asked.


1. Create a new Cloud 9 environment

2. Update the system
   * In the terminal, update the system packages using sudo yum update -y
   ![image](https://github.com/trintambogo/document-search-chatbot/assets/87088123/1865e9da-e689-40a9-add4-30c389b2b1db)

3. If you are using cloud 9, CDK is automatically installed. We can verify that and check its version.
     ![image](https://github.com/user-attachments/assets/c8ce118e-1073-4586-921a-fe0a41d8d81f)

4. BootStrap the AWS environment
   * Sets up an environment with the necessary resources for CDK to operate. It creates resources like S3 buckets and IAM roles which are important for storing deployment assets and managing roles. Without this you will not be able to deploy CDK applications.
   - cdk bootstrap aws://account-id/account-region
       
![image](https://github.com/user-attachments/assets/e97c428d-aabf-404a-b22a-d7b4a24a4aee)



