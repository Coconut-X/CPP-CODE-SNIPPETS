# C++ Code Snippets (By Ali Imran)

**Tired of typing common C++ boilerplate and repetitive code structures?** This VS Code extension provides a comprehensive collection of essential C++ code snippets designed to boost your productivity in competitive programming, general development, and daily coding tasks. Spend less time writing boilerplate and more time solving problems!

## ✨ Features

This extension provides a rich set of snippets for various C++ programming needs:

### 🚀 **Competitive Programming Kickstart**
Get ready for competitive programming challenges in an instant.

* **Boilerplate (Prefix: `boilerplate_comp`)**: Inserts a full competitive programming setup, including a wide range of standard headers, common `using` declarations, fast I/O macros, and type aliases.
    ```cpp
    // Example output for 'boilerplate_comp'
    #include <iostream>
    #include <string>
    // ... many more includes ...
    using namespace std;
    using ll = long long;
    #define fastc ios::sync_with_stdio(false); cin.tie(nullptr);
    #define endl '\n'

    int main(){
        fastc;
        cout<<"I'm Coconut"<<endl; // Or your default main content
        return 0;
    }
    ```
* **Basic Boilerplate (Prefix: `boilerplate`)**: A simpler "Hello, World!" boilerplate for quick starts.
    ```cpp
    // Example output for 'boilerplate'
    #include <iostream>
    using namespace std;

    int main() {
        cout << "Hello, World!" << endl;
        return 0;
    }
    ```
* **Main Function (Prefix: `main`)**: Inserts a standard `int main() {}` structure.
    ```cpp
    // Example output for 'main'
    int main() {
        // Your code here
        return 0;
    }
    ```

### 💬 **Smart `cout` Statements**
Streamline your output with multi-variable `cout` snippets.

* **`cout` (Prefix: `cout`)**: `cout << variable << endl;`
* **`cout2` (Prefix: `cout2`)**: `cout << var1 << var2 << endl;`
* **`cout3` (Prefix: `cout3`)**: `cout << var1 << var2 << var3 << endl;`
* **`cout4` (Prefix: `cout4`)**: `cout << var1 << var2 << var3 << var4 << endl;`
* **`cout5` (Prefix: `cout5`)**: `cout << var1 << var2 << var3 << var4 << var5 << endl;`
    > *Usage Tip*: Type `cout` then `Tab`, fill in the variable. For multiple variables, append the number, e.g., `cout3` and hit `Tab` to navigate through placeholders.
    

### 🔢 **Control Flow & Structures**
Quickly generate common C++ constructs.

* **Integer For Loop (Prefix: `fori`)**: A standard `for (int i = 0; i < n; ++i) {}` loop.
* **Class Template (Prefix: `class`)**: Inserts a basic C++ class definition with constructor and destructor placeholders.
* **Scoped Enum (Prefix: `enum_class`)**: Defines a type-safe `enum class`.
* **Try-Catch Block (Prefix: `tryc`)**: Inserts a `try-catch` block for exception handling.
* **Lambda Function (Prefix: `lambda`)**: A versatile template for C++ lambda expressions.

### 📊 **Vector Utilities**
Efficiently work with `std::vector`s.

* **Declare Vector (Prefix: `vec`)**: `vector<int> name;`
* **Declare Vector with Size (Prefix: `vecs`)**: `vector<int> name(size);`
* **Declare Vector with Size & Value (Prefix: `vecsv`)**: `vector<int> name(size, value);`
* **2D Vector (Prefix: `vec2d`)**: `vector<vector<int>> name(rows, vector<int>(cols, 0));`
* **Vector For Loop (Index) (Prefix: `vfor`)**: Iterate using an index-based `for` loop.
* **Vector For Loop (Range) (Prefix: `vforr`)**: Iterate using a range-based `for` loop.
* **Sort Vector (Prefix: `sortv`)**: `sort(vec.begin(), vec.end());`
* **Reverse Vector (Prefix: `reversev`)**: `reverse(vec.begin(), vec.end());`

### 🐛 **Debugging Aid**
Simplify adding debug print statements.

* **Debug Print (Prefix: `dbg`)**: Inserts `cerr << "DEBUG: var_name = " << var_name << endl;`
---

## 🚀 Installation

1.  Open VS Code.
2.  Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3.  Search for "C++ Code Snippets" (or `cpp-code-snippets`).
4.  Click "Install".

## 🛠️ Requirements

* Visual Studio Code (version `1.101.0` or higher, as per your `package.json`).
* A C++ extension like "C/C++ Extension Pack" by Microsoft is recommended for full language support and IntelliSense, though snippets will work independently.

## ⚙️ Extension Settings

This extension does not contribute any specific VS Code settings.

## ⚠️ Known Issues

Currently, there are no known issues. If you encounter any problems, please open an issue on the [GitHub repository](https://github.com/Coconut-X/CPP-CODE-SNIPPETS/issues).

## 📄 Release Notes

### 0.0.1 (July 5, 2025)
* Initial release of C++ Code Snippets.
* Includes comprehensive competitive programming boilerplate.
* Smart `cout` statements (`cout`, `cout2`, `cout3`, `cout4`, `cout5`).
* Snippets for common control flow (for loops, class, enum class, try-catch, lambda).
* Vector utility snippets (declaration, 2D, iteration, sort, reverse).
* Basic debug print macro.

---

## Contributing

Contributions are welcome! If you have ideas for new snippets or improvements to existing ones, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/Coconut-X/CPP-CODE-SNIPPETS).

## License

This extension is licensed under the [MIT License](https://github.com/Coconut-X/CPP-CODE-SNIPPETS/blob/main/LICENSE). (You'll need to add a LICENSE file to your repo if you want to explicitly state this.)

---

**Enjoy coding with C++ Code Snippets!**

---

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://www.markdownguide.org/basic-syntax/)