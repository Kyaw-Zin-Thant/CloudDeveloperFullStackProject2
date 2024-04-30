# Image Processing Microservice on AWS

This is designed to provide image processing capabilities through a RESTful API hosted on AWS Elastic Beanstalk.

## Overview

This project aims to demonstrate the deployment of an image processing microservice using AWS services. It provides an endpoint to filter images by passing the URL of the image to be processed. The service applies a predefined filter to the image and returns the filtered version.

## Usage

### Main Site

You can access the main site of the microservice at [Image Processing Microservice](http://clouddeveloperfullstackproject2-dev.us-east-1.elasticbeanstalk.com/). .

### Filtered Image

To filter an image, you can use the following URL pattern:

```
http://clouddeveloperfullstackproject2-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=<URL_OF_YOUR_IMAGE>
```

[Filtered Image Example](http://clouddeveloperfullstackproject2-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://image.shutterstock.com/image-photo/diverse-amazon-forest-seen-above-600w-2072628056.jpg)


## Contributors

This project is maintained by Kyaw Zin Thant.
