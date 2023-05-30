# The Alumni Site of the Brown Daily Herald

## Code Structure
This (primarily static) site is structured as follows: Each individual page has its own `html` file, and each of the year pages also have their own corresponding `html` file. 

## Creating a New Page
To create a new page for a year (say, 2019), just create a new file called `<year>.html` and copy and paste the code from any of the previous year pages. Add in the relevant text in the appropriate section(s) - Commencement or End of Year. Then, make sure you add the link to the `years.html` file (so that it is shown in the grid of links), and then re-deploy the website. 

## Hosting
This website is hosted using Amazon S3, which is best for static website hosting. For any questions about deployment, take a look at [this tutorial](https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html#root-domain-walkthrough-s3-tasks), focusing on the part about uploading the files (the other stuff should already be set up). For any questions about the code, reach out to tanvir_shahriar@brown.edu; for any questions about the deployment process or AWS, reach out to rahul_jayaraman@alumni.brown.edu (or rjayaram@mit.edu).