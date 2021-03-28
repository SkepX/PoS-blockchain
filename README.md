# PoS-blockchain
Proof of Stake Blockchain coded in golang.

### Installation:

#### (Linux)
- `git clone https://github.com/SkepX/PoS-blockchain`
- `sudo apt install golang -y`
- `go get github.com/joho/godotenv`
- `go get -u github.com/davecgh/go-spew/spew`
- `cd PoS-blockchain`
- `mv port.env .env`
- `go run main.go`
- open a new terminal window and `nc localhost 9000`
- input token amount
- input a BPM 
- wait a few seconds to see which of the two terminals won.
- open multiple terminals for `nc localhost 9000` and watch Proof of Stake in action!
