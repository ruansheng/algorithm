```
func sort()  {
	score := []int{2,5,2,7,5,8,0,2}

	fmt.Println(score)

	for i := 0; i < len(score); i++ {
		for j := 0; j < len(score) - i - 1; j++{
			if score[j] > score[j + 1] {
				score[j], score[j + 1] = score[j + 1], score[j]
			}
		}
	}

	fmt.Println(score)
}
```

```
func sort()  {
	score := []int{2,5,2,7,5,8,0,2, 9}

	fmt.Println(score)

	for i := 0; i < len(score); i++ {
		for j := len(score) - 2; j >= i; j--{
			if score[j] > score[j + 1] {
				score[j], score[j + 1] = score[j + 1], score[j]
			}
		}
	}

	fmt.Println(score)
}
```

```
func sort()  {
	score := []int{2,5,2,7,5,8,0,2}

	fmt.Println(score)

	for i := 0; i < len(score) - 1; i++ {
		for j := i + 1; j < len(score); j++{
			if score[i] > score[j] {
				score[i], score[j] = score[j], score[i]
			}
		}
	}

	fmt.Println(score)
}
```
