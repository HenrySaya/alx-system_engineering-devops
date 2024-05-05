0x04. Loops, conditions and parsing
============================================

# Loops, conditions and parsing

In this particular bash scripting project I had an overview and understanding of the following:
  * `Loops sample`
  * `Variable assignment and arithmetic`
  * `Comparison operators`
  * `File test operators`
  * `Making scripts portable`

## Tasks :page_with_curl:
* **0. Create a SSH RSA key pair**
  * [0-RSA_public_key.pub](./0-RSA_public_key.pub): This task involved creating a SSH RSA key pair for my linux machine with `ssh-keygen -t rsa` command
	*After creating the key I shared it right here in file `0-RSA_public_key.pub`

* **1. For Best School loop**
  * [1-for_best_school](./1-for_best_school): This is a script that displays `Best School` 10 times using the `for` loop

* **2. While Best School loop**
  * [2-while_best_school](./2-while_best_school): This script displays `Best School` 10 times using the `while` loop

* **3. Until Best School loop**
  * [3-until_best_school](./3-until_best_school): This script displays `Best School` 10 times using the `until` loop

* **4. If 9, say Hi!**
  * [4-if_9_say_hi](./4-if_9_say_hi): This is a bash script that displays `Best School` 10 times but for the 9th iteration it does as such:
	* displays `Best School` and then followed by `Hi` on the newline
	* Used the `while` loop
	* Used if statement for the additional twist

* **5. 4 bad luck, 8 is your chance**
  * [5-4_bad_luck_8_is_your_chance](./5-4_bad_luck_8_is_your_chance): This is a bash script that loops from 1 to 10 with variations based on `The Chinese culture`[moreinfoonChineseCulture](./https://www.chcp.org/Chinese-Numerology) whereby:
	* displays `bad luck` for the 4th iteration
	* displays `good luck` for the 8th iteration
	* displays `Best School` for other iterarions
	* Implemented with the `while` loop
	* incorporated `if, elif` and `else` statements for the Chinese culture

* **6. Superstitious numbers**
  * [6-superstitious_numbers](./6-superstitious_numbers): This script displays numbers from 1 to 20 and:
	* displays `4` *and then* `bad luck from China` for the 4th loop of the iteration
	* displays `9` *and then* `bad luck from Japan` for the 9th loop of the iteration
	* displays `17` *and then* `bad luck from Italy` for the 17th loop of the iteration
  * Requirements:
	* Used the `while` loop
	* used the `case` statement for switch scenarios

* **7.Clock**
  * [7-clock](./7-clock): This script displays the time for 12 hours and 59 minutes:
	* display hours from 0 to 12
	* display minutes from 1 to 59
  * Requirements:
	* Used the `while` loop nested

* **8.For ls**
  * [8-for_ls](./8-for_ls): This script displays:
	* The content of the current directory
	* In a list format
	* Where only the part of the name after the first dash is displayed
  * Requirements:
	* Used the `for` loop
	* Not display hidden files

* **9. To file, or not to file**
  * [9-to_file_or_not_to_file](./9-to_file_or_not_to_file): This is a bash script that gives you information about the `school` file
  * Requirements:
	* Used `if` and, `else`
	* if the file exist: `school file exists`
	* if the file does not exist: `school file does not exist`
	* If the file exists, print:
		* if the file is empty: `school file is empty`
		* if the file is not empty: `school file is not empty`
		* if the file is a regular file: `school is a regular file`
		* if the file is not a regular file: (nothing)
