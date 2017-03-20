FROM ansible/centos7-ansible

MAINTAINER Bryan CS <@iambryancs>

RUN echo "localhost ansible_connection=local" > /etc/ansible/hosts

COPY . /etc/ansible/roles/iambryancs.repo-webtatic

RUN ansible-galaxy install -r /etc/ansible/roles/iambryancs.repo-webtatic/tests/requirements.yml
