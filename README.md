[![Apache 2](http://img.shields.io/badge/license-Apache%202-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![](https://images.microbadger.com/badges/image/janloeffler/html-demo.svg)](http://microbadger.com/images/janloeffler/html-demo)

# html-demo
Example Website for testing purposes


# Build the docker image

    $ docker build -t janloeffler/html-demo:latest -t janloeffler/html-demo:0.5 .

# Check that our docker image works

    $ docker run -p 80:80 -p 443:443 -it janloeffler/html-demo:0.5

Visit [http://localhost/](http://localhost/)! Stop your server with **Ctrl+C**.

# Upload docker image to registry

    $ docker push janloeffler/html-demo:0.5
