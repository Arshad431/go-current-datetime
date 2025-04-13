# Clone the repo
git clone https://github.com/your-username/go-current-datetime.git
cd go-current-datetime

# Add the Go code
echo 'package main

import (
	"fmt"
	"time"
)

func main() {
	currentTime := time.Now()
	fmt.Println("Current Date and Time is:", currentTime.Format("2006-01-02 15:04:05"))
}' > main.go

# Commit and push
git add main.go
git commit -m "Initial commit: display current date and time"
git push origin main
