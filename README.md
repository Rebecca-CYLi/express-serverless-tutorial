
# express-serverless-tutorial

Tutorials:

  1. https://hashnode.com/post/building-a-todo-app-using-reactjs-and-serverless-cjrwd1wio00gur1s2p4zhonmw

  - Used this one
  
    2. https://www.serverless.com/blog/serverless-express-rest-api
    

Tutorial to set up serverless on aws and serverless offline for localhost 

Known bugs for serverless offline:
  - app.get('/index', function (req, res) {
      res.send('Hello World!')
    })
   - can't get '/', '/dev/' : have to do '/dev/index/' to be able to get to root path
   
   - Discussion of bug:
      - https://github.com/dougmoscrop/serverless-http/issues/86#issuecomment-627514571


Killing Ports for reusage:
- http://www.mastertheboss.com/jboss-server/jboss-configuration/solving-javanetbindexception-address-already-in-use-jvmbind
