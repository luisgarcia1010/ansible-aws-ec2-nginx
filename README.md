# ansible-aws-ec2-nginx

# Playbook launch

`ansible-playbook -i hosts playbook/aws-ec2-nginx.yml -e '{ "aws_access_key": XXX }' -e '{ "aws_secret_key": YYY }' -e '{ "web_instance_tags_name": [web1, web2] }'`
