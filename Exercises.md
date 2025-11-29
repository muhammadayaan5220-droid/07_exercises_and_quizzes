# 📝 Final Boss: The Agent Setup Script

Create a Python script (or use a Notebook cell) that performs the following steps.

### Step 1: Define State (Variables)
Create variables for:
* `bot_name` (String): Set it to "CyberBot".
* `version` (Float): Set it to 2.5.
* `battery` (Integer): Set it to 85.
* `online_status` (Boolean): Set it to `True`.

### Step 2: Logic Check (Operators)
Create a variable `is_ready`.
* It should be `True` ONLY if:
    * `battery` is greater than 20
    * AND `online_status` is True.

### Step 3: Formatting (Strings & Casting)
Create a final message using an **f-string**:
* "System Check: [bot_name] v[version]. Ready to launch: [is_ready]"

### Expected Output
```text
System Check: CyberBot v2.5. Ready to launch: True
