package main

import (
	"fmt"
)

func main() {
	slice := []int{1, 2, 3, 4}
	fmt.Println(slice)
	fmt.Println(append(slice, 5, 6))
}

