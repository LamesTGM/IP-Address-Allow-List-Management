# IP Address Allow List Management

## Description
This project demonstrates my ability to automate the management of IP address allow lists using Python. The script reads, updates, and writes IP addresses to an allow list file (`allow_list.txt`), ensuring secure access to restricted content.

## Tools Used
- **Python**: File handling (`with open`, `.read()`, `.write()`), list manipulation (`.remove()`).
- **Text File**: `allow_list.txt` for storing IP addresses.

## Steps
1. **Read the Allow List**:
   - The script reads the current list of allowed IP addresses from `allow_list.txt`.

2. **Update the Allow List**:
   - The script removes unauthorized IP addresses from the list using Python’s `.remove()` method.

3. **Write the Updated Allow List**:
   - The script writes the updated list of allowed IP addresses back to `allow_list.txt`.

## Outcome
- Streamlined the process of managing IP address access.
- Improved security by ensuring only authorized IP addresses are allowed.
- Reduced manual effort and potential errors.
