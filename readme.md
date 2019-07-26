# LexDocs - End User Documentation for  [Lexgate](https://lexgate.ch)

## Installation

To run dev server inside Docker container

    bash ldo up
    
Server is available on host http://localhost:1313/

Tear down dev server
    
    bash ldo down
    
Watcher doesn't work inside container on Windows host machine.
To run watcher on host machine install Hugo https://gohugo.io/getting-started/installing/ and run

    bash ldo watch
    
or to run build without watching

    bash ldo build

you can extend watch and build with more arguments, for example build with drafts:

    bash ldo build -D
[CLI Docs](https://gohugo.io/commands/hugo/)

Update dependencies (Template) with
bash ldo update