# Strings: String to Lowercase


## 📝 Aim
To convert a given string (e.g., `'HELLO'`) into lowercase using basic ASCII manipulation in C.

## 🧠 Algorithm

1. **Declare** a character array `ch` of size 30 and an integer variable `i`.
2. **Read** a string into the array `ch`.
3. **Iterate** through each character of the string using a `while` loop:
   - If the character is uppercase (ASCII range 65 to 90), **convert** it to lowercase by adding 32.
4. **Print** the resulting lowercase string.

## 💻 Program
```
#include <stdio.h>

int main() {
    char ch[30];
    int i = 0;
    printf("Enter a string: ");
    scanf("%s", ch);
    while(ch[i] != '\0') {
        if(ch[i] >= 'A' && ch[i] <= 'Z') {
            ch[i] = ch[i] + 32;
        }
        i++;
    }
    printf("Lowercase string: %s\n", ch);

    return 0;
}
```
## Output
<img width="392" height="275" alt="image" src="https://github.com/user-attachments/assets/5b4e5b0d-fc50-42b0-91d3-a78739ccc794" />

## Result
a given string (e.g., `'HELLO'`) into lowercase using basic ASCII manipulation in C is converted.
