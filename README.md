# webapp-demo
An example web app docker image.

## Usage

##### Build the image
```sh
$ git clone https://github.com/damonkelley/webapp-demo.git
$ cd webapp-demo
$ docker build -t damonkelley/demo .
```
Use whatever namimg convention you like instead of `damonkelley/demo`

##### Run the image in the foreground
```sh
$ docker run -it -p 5000:5000 damonkelley/demo
```

##### Run the image in the background
```sh
$ docker run -d -p 5000:5000 damonkelley/demo
```
 Go to `<dockerhost>:5000` in your browser.

