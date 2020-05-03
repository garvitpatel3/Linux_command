# Linux_command
Linux_command

/************************
    Use linux as web server
*************************/
=> sudo su -
=> yum install httpd -y
=> cd /var/www/html
=> vi index.html
=> <h1>Hi welcome</h1>
=> press Ecs
=> :wq!
=> chmod 755 index.html
=> service httpd start
=> chkconfig httpd on
=> publicip/ index.html

<div style="background-color:red">
        <h1>Linux Machine</h1>
</div>

//node > 
https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html

/************************
    Use Windows  as web server
*************************/
=> Install IIS
=> Install-WindowsFeature -name Web-Server -IncludeManagementTools
=> C:/inetpub/wwwroot/index.html
=> <h1>Hi welcome</h1>
=> publicip/ index.html
