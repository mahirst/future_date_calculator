# Date Calculator

This simple Python script calculates the date that is a specified number of days from the current date.

## Features

- Calculate future dates based on the current date and a given number of days.
- Easy to modify for different time spans.

## Requirements

- Python 3.x

## Usage

1. Import the necessary modules: `datetime` and `timedelta` from the `datetime` library.
2. Get the current date using `datetime.now()`.
3. Calculate the future date by adding a `timedelta` object, specifying the number of days, to the current date.
4. Format the future date as desired using `strftime()`.

## Example

```python
from datetime import datetime, timedelta

# Current date
current_date = datetime.now()

# Calculate the date 33 days from now
future_date = current_date + timedelta(days=33)

# Format the date to display only the day
future_day = future_date.strftime("%A, %B %d, %Y")
print(future_day)
```

In this example, the script calculates the date that is 33 days from the current date and formats it to display the day of the week, month, day, and year.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
