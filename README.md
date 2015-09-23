# Kahoot Hack

**NOTE**: This is a modified git from kahoot-hack

## Tools included

Currently, I have implemented the following tools:

 * crasher.go - freeze the game of kahoot irreversibly
 * flood.go - flood a lobby with a ton of bogus nicknames
 * regular.go - play the game regularly, answering questions as you progress

## How to install the hack:

**Mac OS X**:

Use the almighty terminal ( ͡° ͜ʖ ͡°)

1. Install brew ( http://brew.sh/ )
2. Use brew to install go ( https://golang.org/ ): 
         
         brew install go
3. Define the work space for go

         echo 'export GOPATH=[path]' >> [path]/.profile
         source [path]/.profile
         go env | grep GOPATH
4. Go into the workspace folder

         cd [path]
5. Install the packages to make the hack work 

         go get github.com/padnezz/kahoot-hack-mod
         go get github.com/gorilla/websocket
6. In 

         [workspace path]/src/github.com/padnezz/kahoot-hack-mod 
run diffrent types of files against the Kahoot quiz

         go run flood.go
         go run crash.go
         go run regular.go

         
