# Jay Arun's portfolio

This is my professional portfolio project created on Feb 23 to showcase my skills. It uses AWS and ReactJS

## Technologies Used & trouble shoot issues faced as I progress

1.Git and github
2. SSH
  --> Had difficulties to configure git user name and password since initially ssh-add was not working in my local to add the private key. If when added, I dont have to everytime feed the username & password while checking in the code. Finally I figured out.. yay!!. I came out of portfolio project and navigated to ssh path. Initiated, ssh-agent via eval variant and then tried to add key. It worked. It took may be 20 mins to trouble shoot the issue by going over stack overflow forums. (source : https://stackoverflow.com/questions/17846529/could-not-open-a-connection-to-your-authentication-agent/10077302#10077302)
  --> Though I added SSH key created, its still asking in openSSH console in a pop up window. not sure, this could be security concern on windows
3. HTML
4. CSS
5. Font - Google fonts
6. AWS Route53
 --> I had my domain name registered in different AWS account which was created 2 years ago. In order to use that in my current AWS account, I have to request to transfer domain from previous account to the current account. Once I intiiated this process via AWS support center, a case was created for this and domain was transferred within 6 hrs window to my active account.
 --> Though domain name transfered from old to new acct. I had difficulty in setting up alias target to S3. With S3 endpoint, the webpage worked fine, however when it  was configured in Route 53, it didn't work. Had error "Server IP address not found and err_NAME not resolved while I inspected the webpage". I checked online and figured out that name servers created in hosted zone were not matching with the name servers regiatered in the domain name. After some test & trials, it worked. (source : https://medium.com/serverlessguru/err-name-not-resolved-aws-route-53-abb88c43e884)
