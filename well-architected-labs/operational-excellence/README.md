# Following [Operational Excellence in Well Architected](https://www.wellarchitectedlabs.com/operational-excellence/)

# Troubleshooting

1. When I created for the first time stack on a new account I had an error that request has to be verified first for a given region. Received the email that it was validated, but I couldn't find a button to 're-create' stack, so I deleted it and created a new one. Successfully. Because of failed creation of the stack 3 out 4 instances of EC2 were terminated. Found out that `The instance will remain on the AWS console for about an hour before the system deletes it completely. After you terminate an instance, you will also delete all attached Amazon EBS volumes.` so it means that I don't need to worry that I messed something up. Hopefully.
