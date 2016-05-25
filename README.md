# streamz
This is a demo deployment .war file for the Streama app.

To deploy a fully functional demo version of Streama in OpenShift v3, point
the Tomcat 7 template at this git repo, and that's it!

You'll have a fully functional demo of Streama up and running!

Please keep in mind:

1) Your app will be running on ephemeral storage, so don't get too attached to any of the videos you upload.

2) This is running an internal h2 database. Please use the Streama repo on my page to deploy a Streama instance using mysql.

After you deploy this app, just log in using the default credentials (admin:admin), set your upload folder (try
/data/streama or /home/jboss/upload), set your URL, and begin uploading videos!
