# 🛠 fix-a-bug

## Setup

Clone this repo.

```bash
git clone https://github.com/datamade/fix-a-bug.git && cd fix-a-bug
```

Install the requirements. (Feel free to use a virtual environment!)

```bash
pip install -r requirements.txt
```

Run the tests.

```bash
pytest -sv
```

## Challenge

The code in `fix_me.py` contains four errors that are preventing the test from
passing. Debug and correct each error. As you identify the errors, fill out
a description of the problem and an explanation of the root cause and your fix
in the section below.

### Error 1

**Description:  enumerate function is wrong.**

**Explanation:  when enumerate(some_list), the order is counter, value. The order for counter and value was wrong in the code, I fixed it by changing the order.**


### Error 2

**Description: get_previous() function will return the last value in the list when current_index is 0**

**Explanation: I fixed the function by adding an if statement**

### Error 3

**Description: sum() is used wrong**

**Explanation: we only need to simply add two numbers instead of using the sum function in the code for this case**

### Error 4

**Description: the test-fix-me file is using ParentB as input data while the default input data is ParentA**

**Explanation: I changed the ParentB as the default input for the Transformer class**
