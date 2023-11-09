# String Methods Reference

| JavaScript             | Python                        | C++                                      |
|------------------------|-------------------------------|------------------------------------------|
| `charAt(index)`        | `s[index]` or `s.at(index)`   | `s.at(index)`                            |
| `charCodeAt(index)`    | `ord(s[index])`               | `static_cast<int>(s[index])`             |
| `concat(str1, str2)`   | `s1 + s2`                     | `s1 + s2`                                |
| `indexOf(substring)`   | `s.find(substring)`           | `s.find(substring)`                      |
| `slice(start, end)`    | `s[start:end]`                | `s.substr(start, length)`                |
| `toUpperCase()`        | `s.upper()`                   | `std::transform(s.begin(), s.end(), s.begin(), ::toupper)` |
| `toLowerCase()`        | `s.lower()`                   | `std::transform(s.begin(), s.end(), s.begin(), ::tolower)` |
| `trim()`               | `s.strip()`                   | `s.erase(std::remove_if(s.begin(), s.end(), ::isspace), s.end())` |
| `split(separator)`     | `s.split(separator)`          | `std::istringstream(s) >> std::skipws >> item` |
| `replace(search, replacement)` | `s.replace(search, replacement)` | `std::replace(s.begin(), s.end(), search, replacement)` |

*Note: The provided equivalences are general and may vary based on specific use cases and requirements.*

