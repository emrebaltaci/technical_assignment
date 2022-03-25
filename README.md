# PROJECT-USER INTERFACE SPESIFICATION
This is the user interface specification document, which is want in technical assignment
## Requierements
* SQL-Database
* UI Labor
 **offline!**

## Page Design
The page have 3-side; up,down-left, down-right.
* Up side covers of up side of page. Up side specs. is explained as detailed in following:
	*  The page height is selected as around 40 pixel, width is what of window size.
	 * The page rgb code of background color is selected as 230,230,230.
	 * Button-1 is added to left side of UP. Button specs. are following:
		 * Button-1 has a condition and is explained in Condition section as Condition-1
		 * Button-1 rgb code is selected as 0,136,235.
		 * Button-1 has a text as "+ New User", the text is centered of button, text color is white.
		 * Left-top corner of button-1 location is 5,15 pixel.
		 * Button-1 size 30,70 pixel.
	* Right side of button-1, checkbox-1 and text is located. It's specs. are detailly explained in the following:
		* Checkbox-1 is saves it's condition. 
		* Checkbox-1 has a condition and is explained in Condition section as Condition-2 
		* checkbox-1 up-left location is 20,125 pixels.
		* Text's up-left location is 20,140 pixels.
		* Text color is black and text is "Hide Disabled User".
	* Button-2 is located in right side of UP side.
		* Button-2 has a text as "Save User" and text color is white.
		* Button-2's up-right side of is location is 5,20 of UP right side.
		* Button-2 has a condition and is explained in Condition section as Condition-3.
		* Button-2's background color RGB code is 0,210,255.
* Down-Left side is pull side data from Server.
	* The visual format Table-1 as 4 column. Column topics are "ID", "User Name", "Email", "Enabled", and topics color is white. In the topics row the color is 0,136,235, as rgb format.
	* Column shape is shared in the following:
		| i ID | User Name | Email | Enabled |
		| :-----: | :---------: | :-------: | :-----: |
		|i iindex1 | user1 |email1 |true |
		|i iindex2 |user2 |email2 |false |
	*	Each row index, background toggles as white and rgb 0,136,235.
*	Down-Right side is used for push data to server. Down-Right side has 2 part; Up(Topic) and Down.
	*	Up side has background as 230,230,230 as rgb format.
		*	A text is available as "New User" topic, and color is black.
		* Text up-left corner starts at this up side 20,10 pixel coordinates.
	* 	Down side is input side. There is a list of item row names(left region) and it's input field(right region). 
		* First item is "Username:" text and it's text color is black. Input field box size as 20,320 pixel size.
		* Second item is "Display Name:" text and it's text color is black. Input field box size as 20,320 pixel size.
		* Third item is "Phone:" text and it's text color is black. Input field box size as 20,320 pixel size.
		* Fourth item is "Email:" text and it's text color is black. Input field box size as 20,320 pixel size.
		* Fifth item is "User Roles:" text and it's combobox input box size as 20,320 pixel size.
			* In default combobox gives an info as "Select user roles..." text
			* Combobox has 3 items as "Guest", "Admin", "SuperAdmin".
		* Sixth item is "Enabled:" text and its' text color is black. Input is checkbox-2. The checkbox-2 has disabled in default condition
