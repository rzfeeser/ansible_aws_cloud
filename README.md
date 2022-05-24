# Ansible for AWS Cloud
Lifecycle an Amazon AWS S3 bucket and learn about Ansible.

### Author
@RZFeeser

### To use
To build the "jellytoaster76", run the following:
`ansible-playbook playbook_s3_bucket.yml`

To remove the "jellytoaster76", Run the following:
`ansible-playbook -e "hereorthere=absent" playbook_s3_bucket.yml`

### Authorization notes
- If you use this solution within AWX or Ansible Tower, simply use the credential associated with Amazon AWS Cloud. The playbook is setup to read the necessary credentials.
- If you are using this solution manually, you will need to define the variables `access_key` and `secret_key` with your AWS keys (see your AWS account for these).
