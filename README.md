# Cloudfront KeyValueStore Redirect

The following project is a quick proof of concept of using a
Cloudfront distribution + Cloudfront function with the new
[Cloudfront KeyValueStore][blog] to create edge ready redirect
application.

As Cloudfront KeyValueStore was released yesterday, its resource definitions do
not exist in IaC providers so I had to create that part via the console.

[blog]: https://aws.amazon.com/blogs/aws/introducing-amazon-cloudfront-keyvaluestore-a-low-latency-datastore-for-cloudfront-functions/
