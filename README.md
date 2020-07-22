
# newexpress
Tutorial to set up serverless on aws and serverless offline for localhost 

Known bugs for serverless offline:
  - app.get('/index', function (req, res) {
      res.send('Hello World!')
    })
   - can't get '/', '/dev/' : have to do '/dev/index/' to be able to get to root path
