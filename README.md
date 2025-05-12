
# Animated ASCII Name Printer ✨

This Java program takes a custom input (your name or any word) and prints it in animated ASCII art style using console output. Each letter is drawn using asterisks (`*`) with a configurable delay for animation.

## 🚀 Features

- ✅ Displays animated letters A–Z using star patterns
- ✅ Custom user input for names
- ✅ Adjustable animation speed using delay
- ✅ Fully written in Java with no external libraries
- ✅ Easy-to-read and extendable structure
- ✅ Separate functions for each character

## 🖥️ Sample Output

For input: `ABC`

```
  * * * * *      * * * * * *        * * * * * *    
*           *    *           *    *
*           *    *           *    *
* * * * * * *    * * * * * *      *
*           *    *           *    *
*           *    *           *    *
*           *    * * * * * *        * * * * * *  

```

## 🛠️ How It Works

- Each character from A to Z has a corresponding function (e.g., `A(int i)`, `B(int i)`, etc.).
- The input string is taken at runtime and processed one row at a time.
- On each row iteration, all characters are printed side-by-side to resemble the structure of the word.
- Optional animation is achieved using `Thread.sleep(delay)`.

## 📦 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/armanali485/Animated-ASCII-Name-Printer
cd Animated-ASCII-Name-Printer
```

2. **Compile and run:**

```bash
javac PrintingName.java
java PrintingName
```

3. **Enter your custom input:**

```
Enter your name : Arman Ali
```
## 🖥️ Output

For input: `Arman`

```
  * * * * *      * * * * * *      *           *      * * * * *      *           *            * * * * *      *                * * * * * * *    
*           *    *           *    * *       * *    *           *    * *         *          *           *    *                      *
*           *    *           *    *   *   *   *    *           *    *   *       *          *           *    *                      *
* * * * * * *    * * * * * *      *           *    * * * * * * *    *     *     *          * * * * * * *    *                      *
*           *    *       *        *           *    *           *    *       *   *          *           *    *                      *
*           *    *         *      *           *    *           *    *         * *          *           *    *                      *
*           *    *           *    *           *    *           *    *           *          *           *    * * * * * * *    * * * * * * *    
```
 


## 🚀 Getting Started

## 📝 Requirements

- Java 8 or above
- Terminal or Command Prompt


### ⏱️ Customizing Delay

Change the animation delay by editing the following line in the code:

```java
static int delay = 100; // delay in milliseconds
```

Lower the number for faster animation, or increase for slower.

## 📂 File Structure

```
Animated-ASCII-Name-Printer/
│
├── PrintingName.java    # Main class with character logic
└── README.md            # Project documentation
```

## 👤 Author

**Arman Ali**
📧 [armanali485.hitcsecs2020@gmail.com](mailto:armanali485.hitcsecs2020@gmail.com)
📱 +91 9708244938

---

© 2025 Arman Ali. All rights reserved.







