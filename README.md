<div align="center">

## Full list of ServerVariables


</div>

### Description

You can get all sorts of useful information on the browser, using Request.Servervariables. However, one of the problems with the Visual Interdev help is that it doesn't list ALL the information you can get. Here is the most complete list I know of...if you have any additions, please feel free to append them as a comment!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Beginner
**User Rating**    |4.1 (29 globes from 7 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-full-list-of-servervariables__4-7163/archive/master.zip)





### Source Code

<p><font face="arial,helvetica" size="2"><b>ALL_HTTP</b> are all HTTP headers
sent by the client. <br>
<br>
<b>ALL_RAW</b> retrieves all headers in the raw-form. <br>
<br>
<b>APPL_MD_PATH</b> retrieves the metabase path. <br>
<br>
<b>APPL_PHYSICAL_PATH</b> retrieves the physical path corresponding to the
metabase path. <br>
<br>
<b>AUTH_PASSWORD</b> is the value entered in the client's authentication dialog.
<br>
<br>
<b>AUTH_TYPE</b> is the authentication method that the server uses to validate
users. <br>
<br>
<b>AUTH_USER</b> is the raw authenticated user name. <br>
<br>
<b>CERT_COOKIE</b> is an unique ID for client certificate which is returned as a
string. <br>
<br>
<b>CERT_FLAGS</b> is where bit0 is set to 1 if the client certificate is
present, and bit1 is set to 1 if the certifying authority of the client
certificate is invalid. <br>
<br>
<b>CERT_ISSUER</b> is the issuer field of the client certificate. <br>
<br>
<b>CERT_KEYSIZE</b> is the number of bits in Secure Sockets Layer connection key
size. <br>
<br>
<b>CERT_SECRETKEYSIZE</b> is the number of bits in the server certificate
private key. <br>
<br>
<b>CERT_SERIALNUMBER</b> is the serial number field of the client certificate.
<br>
<br>
<b>CERT_SERVER_ISSUER</b> is the issuer field of the server certificate. <br>
<br>
<b>CERT_SERVER_SUBJECT</b> is the subject field of the server certificate. <br>
<br>
<b>CERT_SUBJECT</b> is the subject field of the client certificate. <br>
<br>
<b>CONTENT_LENGTH</b> is the length of the content header as sent by the client.
<br>
<br>
<b>CONTENT_TYPE</b> is the data type of the content. <br>
<br>
<b>GATEWAY_INTERFACE</b> is the revision of the CGI specification used by the
server. <br>
<br>
<b>HTTP_<<i>HeaderName</i>></b> is the value stored in the header <i>HeaderName</i>.
<br>
<br>
<b>HTTP_ACCEPT</b> returns the value of the Accept header. <br>
<br>
<b>HTTP_ACCEPT_ENCODING</b> returns the value of the Accept encoding. <br>
<br>
<b>HTTP_ACCEPT_LANGUAGE</b> returns a string that specifies the language to be
used for displaying content. <br>
<br>
<b>HTTP_CONNECTION</b> returns a string containing information about the
connection. <br>
<br>
<b>HTTP_COOKIE</b> returns the cookie string that was included with the request.
<br>
<br>
<b>HTTP_HOST</b> returns a string containing information about the host. <br>
<br>
<!--
<b>HTTP_PRAGMA</b> CAN FIND NO INFO ABOUT THIS??????????
<br><br>
--><b>HTTP_REFERER</b> returns a string containing the original URL when a
redirect has occurred. <br>
<br>
<b>HTTP_USER_AGENT</b> returns a string describing the browser used to send the
request. <br>
<br>
<b>HTTP_UA_PIXELS</b> returns a string detailing the screen resolution of the
user agent. <br>
<br>
<b>HTTP_UA_COLOR</b> returns a string with color information. <br>
<br>
<b>HTTP_UA_OS</b> returns a string stating the operating system of the user
agent. <br>
<br>
<b>HTTP_UA_CPU</b> returns a string stating the processor type used by the user
agent. <br>
<br>
<b>HTTPS</b> returns ON if the request came in through secure channel or OFF if
the request is through a non-secure channel. <br>
<br>
<b>HTTPS_KEYSIZE</b> is the number of bits in Secure Sockets Layer (SSL)
connection key size. <br>
<br>
<b>HTTPS_SECRETKEYSIZE</b> is the number of bits in server certificate private
key. <br>
<br>
<b>HTTPS_SERVER_ISSUER</b> is the issuer field of the server certificate. <br>
<br>
<b>HTTPS_SERVER_SUBJECT</b> is the subject field of the server certificate. <br>
<br>
<b>INSTANCE_ID</b> is the ID for the Internet Information Server (IIS) instance
in text format. <br>
<br>
<b>INSTANCE_META_PATH</b> is the metabase path for the instance of Internet
Information Server (IIS) that responds to the request. <br>
<br>
<b>LOCAL_ADDR</b> returns the server address on which the request came in. <br>
<br>
<b>LOGON_USER</b> is the Windows account that the user is logged into. <br>
<br>
<b>PATH_INFO</b> is extra path information as given by the client. <br>
<br>
<b>PATH_TRANSLATED</b> is a translated version of <b>PATH_INFO</b> that takes
the path and performs any necessary virtual-to-physical mapping. <br>
<br>
<b>QUERY_STRING</b> is the query information stored in the string following the
question mark (?) in the HTTP request. <br>
<br>
<b>REMOTE_ADDR</b> is the Internet Protocol (IP) address of the remote host
making the request. <br>
<br>
<b>REMOTE_HOST</b> is the name of the host making the request. <br>
<br>
<b>REMOTE_USER</b> is an unmapped user-name string sent in by the user. <br>
<br>
<b>REQUEST_METHOD</b> is the method used to make the request. <br>
<br>
<b>SCRIPT_NAME</b> is a virtual path to the script being executed. <br>
<br>
<b>SERVER_NAME</b> is the server's host name, Domain Name Server (DNS) alias, or
Internet Protocol (IP) address. <br>
<br>
<b>SERVER_PORT</b> is the port number to which the request was sent. <br>
<br>
<b>SERVER_PORT_SECURE</b> is a string that contain a 1 if the request is being
handled on the secure port, otherwise it is 0. <br>
<br>
<b>SERVER_PROTOCOL</b> is the name and revision of the request information
protocol. <br>
<br>
<b>SERVER_SOFTWARE</b> is the name and version of the server software that
answers the request and runs the gateway. <br>
<br>
<b>URL</b> is the base portion of the URL.</font></p>

