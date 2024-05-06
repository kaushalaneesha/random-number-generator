## Simple Dice Rolling Utility

This is a web-based tool written in PHP that lets you simulate dice rolls. You can specify the number of dice and the number of sides on each die, and it displays the results of each individual roll along with the total sum.

**Features:**

* Roll any number of dice with any number of sides (within reason) through a user-friendly interface.
* See individual results for each die roll.
* View the total value of all the dice rolled.

**How to Use:**

1. **Setup:**
   * Copy the PHP and HTML files (`role_dice.php` and `index.html`) to a web server directory accessible by your browser. 
   * If you're using a local server like XAMPP or MAMP, this might be something like `http://localhost/your_directory/index.html`.

2. **Usage:**
   * Open the `index.html` file in your web browser.
   * Enter the number of dice you want to roll in the "Number of Dice" field.
   * Enter the number of sides on each die in the "Dice Sides" field.
   * Click the "Roll Dice" button.

   The page will display the results of each individual die roll and the total sum.

**Example:**

* Enter "2" in the "Number of Dice" field.
* Enter "6" in the "Dice Sides" field.
* Click "Roll Dice".

The page might show something like:

```
Rolled 2d6: [5, 4] (Total: 9)
```

**Further Enhancements (Optional):**

* Implement error handling for invalid inputs (e.g., non-positive numbers for dice count or sides). This can be done using PHP's built-in functions for data validation.
* Allow for different die types (e.g., d4, d8, d10, etc.) by adding options to the HTML form and modifying the PHP script to handle the different dice types. 