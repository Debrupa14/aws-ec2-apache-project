# aws-ec2-apache-project
My first AWS EC2 Apache web server project
# AWS EC2 Apache Web Server Deployment

## Project Overview
This project demonstrates how to deploy
a static HTML website on an AWS EC2 Linux
instance using Apache Web Server.

## Technologies Used
- AWS EC2
- Amazon Linux 2023
- Apache HTTP Server
- Git
- GitHub
- HTML and CSS
- Linux

## Project Steps
1. Created an AWS EC2 instance.
2. Connected to Linux using SSH.
3. Installed Apache Web Server.
4. Created an HTML website.
5. Configured AWS Security Groups.
6. Deployed the website.
7. Tested website accessibility.

## Linux Commands

sudo dnf update -y
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
sudo systemctl status httpd

## Result
Successfully deployed a static website
using AWS EC2 and Apache.
