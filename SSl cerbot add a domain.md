# Add a domain to existing certificate on nginx

If a certificate already created for the url kibana.sitelinsights.com and you want to add the www.sitelinsights.com to the same domain.
then type the following into the terminal

<code>
certbot -cert-name kibana.sitelinsights.com -d www.sitelinsights.con,kibana.sitelinsights.com
</code>
