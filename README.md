<!-- ABOUT THE PROJECT -->
## Leapforce - HubSpot CMS Developer Assessment

![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/leapforce-preview.png?raw=true)

CTA Section - Two Blocks based on a design system provided in Figma. The task involves creating a section that adheres to the provided design.

## Module Settings and Usage

This section features 3 custom and 1 built in drag and drop modules:
* Heading
* CTA
* Two Column Module
* Richtext

### 01 - Heading

#### Content
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/heading.png)

Custom fields:
* Heading Label
  * Show Label - [Checkbox] Toggle to show heading label or hide
  * Text - [Text] Main Heading label text
* Heading
  * Show Heading - [Checkbox] Toggle to show heading or hide
  * Heading Type - [Dropdown] Choose from heading type to use.
  * Text - [Text] Main Heading text, wrap text with "span" to add secondary font and extra styling.
 
#### Styles
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/heading-styles.png)

Fields:
* Alignment - [Alignment] Align text to left, center and right
* Heading Label - [Font Group] Style heading label font size, font and color, weight etc
* Heading Label - [Font Group] Style heading font size, font and color, weight etc

### 02 - CTA

#### Content
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/cta.png)

Custom fields:
* Button Link - [URL] Configure the button URL
* Button Text - [Text] Main CTA Text
* Icon - [Icon] Choose Button Icon
* CTA Type - [Choice] Choose between Outline and Main CTA
 
#### Styles
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/cta-style.png)

Fields:
* Text - [Font Group] Style Button text, font, color etc.
* Background - [Color] Stlye Button background
* Border - [Border Group] Style Button border width, border color etc.
* Corner - [Number] Style Button border radius
* Spacing - [Spacing] Add padding and margin to Button
* Alignment - [Alignment] Align Button horizontaly to left, center and right.


### 03 - Two Column Module

#### Content
![Two Column Module - HubDB](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/two-col-hubdb.png)
![Two Column Repeater](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/two-col-repeater.png)

Custom fields - HubDB Content Type:
* Cards Content Source - [Choice] Choose between HubDB Table and Repeater content for cards
* Card HubDB Table - [HubDBTable] This field uses HubDB Table with rows and columns:
  * Card Image (card_image) - [Image] required
  * Title (title) - [Text] required
  * Subtitle (subtitle) - [Text] required
  * Card Link (card_link) - [URL] required
* Card Settings - [Group]
  * Card Icon - [Icon] This is the card button icon
  * Open Link In New Tab - [Checkbox] Check if it should open the link in another tab or not
 
Custom fields - Repeater Content Type:

![Two Column Repeater Fields](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/two-col-repeater-1.png)

* Card Image - [Image]
* Title - [Text] Card title
* Subtitle - [Subtitle] Card subtitle
* Card Link - [URL] Card Link
* Card Icon - [Icon] This is the card button icon
 
#### Styles
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/two-col-style.png)

Fields:
* Spacing - Add spacing to the card parent wrapper.
* Card - [Style Group]
  * Corner - [Number] Style Button border radius
  * Title - [Font Group] Add styles to the card title including fonts, color, size etc.
  * Subtitle - [Font Group] Add styles to the card subtitle including fonts, color, size etc.
  * Button - [Style Group]
    * Button Size - [Number] Increase or decrease the size of the button.
    * Icon Size - [Number] Increase or decrease the size of the button icon
    * Color - [Color] Change button color
    * Hover Color - [Color] Change button hover color
   
### 04 - Richtext

#### Content
![alt text](https://143165537.fs1.hubspotusercontent-eu1.net/hubfs/143165537/richtext.png)

This is a built-in HubSpot Module:
 
### Project Preview
Link: [Preview live website](http://143165537.hs-sites-eu1.com/leapforce-assessment)
