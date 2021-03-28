# PoS-blockchain
Proof of Stake Blockchain coded in golang.

### Installation:

####    (Linux)
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

### Screenshots:

#### Genesis Block
![screen](https://raw.githubusercontent.com/SkepX/PoS-blockchain/main/images/image_3.jpg)

#### Token Balance to stake
![screen](https://raw.githubusercontent.com/SkepX/PoS-blockchain/main/images/image_2.jpg)

#### Assigned address
![screen](https://raw.githubusercontent.com/SkepX/PoS-blockchain/main/images/image_1.jpg)

#### Winner Validator
![screen](https://raw.githubusercontent.com/SkepX/PoS-blockchain/main/images/image_4.jpg)

