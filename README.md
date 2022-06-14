## Compare Cloud-Optimized Geotiffs from Amazon Sustainability Data Initiative (ASDI) hosted on S3 using SageMaker Studio Lab (SMSL)  

This demo shows possible solutions to access and use the free accessible data hosted on AWS S3 under the Amazon Sustainability Data Initiative (ASDI) and how to analyze it in AWS Sagemaker Studio Lab.
The Amazon Sustainability Data Initiative (ASDI) seeks to accelerate sustainability research and innovation by minimizing the cost and time required to acquire and analyze large sustainability datasets. ASDI supports innovators and researchers with the data, tools, and technical expertise they need to move sustainability to the next level.

- In this demo, we will be using Sage Maker Studio Lab to explore an example of how AWS cloud can help us extract information from sustainability-relevant open data hosted on AWS. 
- Specifically we will use data from Sentinel-1 from the Amazon Sustainability Data Initiative catalog:
    https://registry.opendata.aws/sentinel-1-rtc-indigo/
- In this case, we are interested in learning how to connect to S3, fetch some data from a specific date and location, and visualize the change of a geolocation over time in the notebook.

You can access it directly:

<a href="https://studiolab.sagemaker.aws/import/github/https://github.com/aws-samples/asdi-smsl-demo-delta/blob/main/Compare-GeoTiffs-S3.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/8c5378ff3bf6f71a57442940234293bd63c7ed2418d64f74f2bda3dc6f2904ed/68747470733a2f2f73747564696f6c61622e736167656d616b65722e6177732f73747564696f6c61622e737667" alt="Open In SageMaker Studio Lab" data-canonical-src="https://studiolab.sagemaker.aws/studiolab.svg" style="max-width: 100%;"></a></p>

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.


A special thanks to the creators of the ressources I used:
- <a href="https://notebooks.githubusercontent.com/view/ipynb?browser=chrome&color_mode=auto&commit=142ed94574aa85339e9cd4d6779986cd8974cb36&device=unknown&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f73636f74747968712f73656e74696e656c312d7274632f313432656439343537346161383533333965396364346436373739393836636438393734636233362f53656e74696e656c312d5254432d6578616d706c652e6970796e62&logged_in=false&nwo=scottyhq%2Fsentinel1-rtc&path=Sentinel1-RTC-example.ipynb&platform=android&repository_id=306456114&repository_type=Repository&version=101">Explore Sentinel-1 RTC AWS Public Dataset</a>
- <a href="https://github.com/pangeo-data/cog-best-practices">Cloud Optimized GeoTiffs Best Practices</a>