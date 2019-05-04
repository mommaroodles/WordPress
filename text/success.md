**Admin Panel**: [${env.url}wp-admin/](${env.url}wp-admin/)  
**Login**: ${user.email}  
**Password**: ${globals.ADMIN_PASSWD}  

To add custom domain name for your WordPress installation, add an A record pointing to the Application Server IP,
or a CNAME pointing to ${env.domain}.
