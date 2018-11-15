# CV website for Guillaume Lam

The website is built using the go framework called Hugo. Using hugo allows for the website to be statically compiled allowing github to host it for me charge-free. The Hugo framework allows for the whole website to be changed in the *config.toml* file using some html to render the text in the sections desired. 

## Running the website 

There are two ways to run the website locally and remotely. 

### Locally

This will be the desired way to change the website and verify that the changes are the right changes. Using the hugo command: 

```
hugo server 
```

in the root folder of the project, hugo will host the website on a localhost port with livereload, allowing for easy development.

### Remotely

This version of remote deployment will push the website to a github repo which hosts the website. To deploy the new changes to the remote website simply run the deploy script at the root of the folder:

```
./deploy.sh
```

The new website will now be present at the address **guillaumelam.com**.
