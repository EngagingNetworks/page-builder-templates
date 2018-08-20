<span id="anchor"></span>Template Primer

The 4Site template consists of minimal page structure markup (3 divs and a logo) and one JS and one CSS file located in the footer of the template. The Javascript has no dependencies. The template can be found in 4Site's Demo Account under the template folder "4Site Templates" and the template name "4Site Template". This template works across Donation pages, Targeted Advocacy Actions, Custom Target Advocacy Actions, Petitions, Email Sign Up pages, Unsubscribe pages, and Data Capture pages. This template has also been tested and supports all standard EN input field types. Testing pages can be found in 4Site's Demo Account under the "Manage Pages" section in the "4Site Template Demo Pages" folder.

**Important Notes:** The template JS and CSS have not been minified but in your set up you will want to do this.

<span id="anchor-1"></span>

<span id="anchor-2"></span>Code Repositories

-   Page Template

    -   [*https://github.com/4site-interactive-studios/Engaging-Networks-Page-Template*](https://github.com/4site-interactive-studios/Engaging-Networks-Page-Template)

-   Email Templates

    -   [*https://github.com/4site-interactive-studios/Engaging-Networks-Email-Template*](https://github.com/4site-interactive-studios/Engaging-Networks-Email-Template)

<span id="anchor-3"></span>Template Testing Pages

-   Donate Single Step

    -   [*https://e-activist.com/page/14268/donate/1*](https://e-activist.com/page/14268/donate/1)

-   Donate Multi Step

    -   [*https://e-activist.com/page/14730/donate/1*](https://e-activist.com/page/14730/donate/1) (Basic)

    -   [*https://e-activist.com/page/14765/donate/1*](https://e-activist.com/page/14765/donate/1) (Fancy)

-   Advocacy Letter to Custom Target

    -   [*https://e-activist.com/page/14270/action/1*](https://e-activist.com/page/14270/action/1)

-   Advocacy Target Based on Postal Code

    -   [*https://e-activist.com/page/14271/action/1*](https://e-activist.com/page/14271/action/1)

-   Petition

    -   [*https://e-activist.com/page/14272/petition/1*](https://e-activist.com/page/14272/petition/1)

-   Newsletter Subscribe

    -   [*https://e-activist.com/page/14760/subscribe/1*](https://e-activist.com/page/14760/subscribe/1)

-   Newsletter Unsubscribe

    -   [*https://e-activist.com/page/14761/subscriptions/1*](https://e-activist.com/page/14761/subscriptions/1)

-   All Input Fields

    -   [*https://e-activist.com/page/14269/data/1*](https://e-activist.com/page/14269/data/1)

<span id="anchor-4"></span>Set Up for Donation Pages

<span id="anchor-5"></span>Section: Gift Frequency and Amount

Text Block

-   &lt;h2&gt;Gift Frequency and Amount&lt;/h2&gt;

Form Block, class="recurring-payment", label position "Above field"

-   Recurring Payment, Radio

    -   Give Once, value ""
    -   Monthly, value "Y"

        -   This may be payment processor dependent.

-   Recurring Day (hidden), Hidden

-   Recurring Frequency (hidden), Hidden

<span id="anchor-6"></span>Dependencies

If Recurring Payment == Y
Set Recurring Frequency (hidden) to "MONTHLY"

This may be payment processor dependent.

If Recurring Payment ==
Set Recurring Frequency (hidden) to ""

Form Block, class="donation-amt", label position Default

-   Donation Amount, Radio with Input

    -   25, value "25"
    -   50, value "50"
    -   100, value "100"
    -   150, value "150"
    -   Surprise Us!, value ""
-   Payment Currency (hidden), Hidden

    -   Default: USD

<span id="anchor-7"></span>Section: Personal Information

Text Block, class="personal-information-title"

-   &lt;h2&gt;Personal Information&lt;/h2&gt;

Form Block, class="personal-information", label position "Above field"

-   First Name

-   Last Name

-   Email Address

<span id="anchor-8"></span>Section: Address

Text Block, class="address-title"

-   &lt;h2&gt;Address&lt;/h2&gt;

Form Block, class="address", label position "Above field"

-   Address 1

-   Address 2

-   City

-   Region, Select

    -   List loaded from EN database. Will be payment processor dependent.
-   Postal Code

-   Country, Select

    -   List loaded from EN database. Will be payment processor dependent.

<span id="anchor-9"></span>Section: Payment Information

Text Block, class="payment-information-title"

-   &lt;h2&gt;Payment Information&lt;/h2&gt;

Form Block, class="payment-information", label position "Above field"

-   Payment Type, Select

    -   Visa, value "VI"
    -   Mastercard, value "MC"
    -   Discover, value "DI"
    -   Amex, value "AX"
-   Credit Card Number, Text

-   Credit Card Expiration, Spit select

    -   Select \#1

        -   01, value "01"

        -   02, value "02"

        -   03, value "03"

        -   04, value "04"

        -   05, value "05"

        -   06, value "06"

        -   07, value "07"

        -   08, value "08"

        -   09, value "09"

        -   10, value "10"

        -   11, value "11"

        -   12, value "12"

    -   Select \#2

        -   2017, value "2017"

        -   2018, value "2018"

        -   2019, value "2019"

        -   2020, value "2020"

        -   2021, value "2021"

        -   2022, value "2022"

        -   2023, value "2023"

        -   2024, value "2024"

        -   2025, value "2025"

        -   2026, value "2026"

-   Credit Card Verification Value, Text

Text Block, class="newsletters-title"

-   &lt;h2&gt;Newsletters&lt;/h2&gt;

Form Block, class="newsletters", label position "Above field"

-   This is where you can drop in your Newsletter Opt-Ins

-   Enable Submit Button

<span id="anchor-10"></span>

<span id="anchor-11"></span>Set Up for Advocacy Pages

<span id="anchor-12"></span>Section: Personal Information

Text Block, class="personal-information-title"

-   &lt;h2&gt;Personal Information&lt;/h2&gt;

Form Block, class="personal-information", label position "Above field"

-   First Name

-   Last Name

-   Email Address

<span id="anchor-13"></span>Section: Address

Text Block, class=""address-title"

-   &lt;h2&gt;Address&lt;/h2&gt;

Form Block, class="address", label position "Above field", Margin 0 0 2rem 0

-   Address 1

-   Address 2

-   City

-   Region, Select

    -   List loaded from EN database. Will be payment processor dependent.
-   Postal Code

-   Country, Select

    -   List loaded from EN database. Will be payment processor dependent.

<span id="anchor-14"></span>Section: Message(s)

Text Block, class=" view-message"

-   &lt;p&gt;&lt;button aria-expanded="false" class="btn btn--view-message" id="viewMessage" role="tab" type="button"&gt;View Message Details&lt;/button&gt;&lt;/p&gt;

Text Block, class="newsletters-title"

-   &lt;h2&gt;Newsletters&lt;/h2&gt;

Form Block, class="newsletters", label position "Above field"

-   This is where you can drop in your Newsletter Opt-Ins

-   Enable Submit Button

<span id="anchor-15"></span>Expanded Documentation

**Only applicable to some instances of the page templates**

Split Header (Screenshot: [*https://d.pr/i/iGevr3*](https://d.pr/i/iGevr3))

-   Two Column Advanced Row:

    -   Column 1 Class: header-logo

    -   Column 2 Class: header-secondary-cta

        -   Optional class to hide on smaller screens: hide-medium
        -   Optional class for Social Sharing section: social-share

-   Note when inserting the logo you may want to use a Data URI to guarantee your logo is always visible.
-   Note "header-secondary-cta" will format two consecutive &lt;p&gt; tags as seen in the screenshot. The first line will have its font style set to bold.

Banner Image with text Overlay (Screenshot: [*https://d.pr/i/xW14VS*](https://d.pr/i/xW14VS) / [*https://d.pr/i/gghxJX*](https://d.pr/i/gghxJX))

-   To make this section editable in EN page builder, each section is displayed in sequence when editing. The first being the banner image, followed by the two text overlay sections. The text overlay sections are optional and can be added singarly or together.
-   One Column Advanced Row:

    -   Column 1 Class: banner image-300h row-breakout

    -   Image: Any inserted image will occupy full width of section. "Row breakout" makes the image go to the edge of the form versus the padding seen elsewhere.

    -   Headline 1: banner-text blue lead

        -   Defaults to the color black text on a transparent background but can be defined as "black", "blue", or "red"
        -   "lead" is used when there are multiple "banner-text" sections to force spacing between them
    -   Headline 2: banner-text black

        -   For the example we use:

            -   &lt;p&gt;Help Make a&nbsp;Difference&nbsp;for&lt;br /&gt;the Future of Our Ocean&lt;/p&gt;

            -   This forces text to wrap, but also for some words to be held (&nbsp;) together when the text resizes. There is no easy way to automate this and it needs to be handled on a per instance basis depending on the text.

Main Body and Form Blocks

-   Main Body Copy and Form Block

    -   One Column Advanced Row:

        -   Column 1 Class: indented-body

            -   Further indents (left, right margins) the contents of the element

-   Giving Frequency

    -   Form Class: recurring-payment radio-to-buttons en-row-center dark-buttons pill-buttons

-   Giving Amount

    -   Form Class: donation-amount radio-to-buttons en-row-center show-hidden-input round-buttons

-   Body Copy

    -   Text Block Class: body-copy click-to-expand

Form Elements

Each of the "Personal Information" input form elements can be added to a single EN Page Builder "Form" field or more granularly each row can be added individually only with the inputs for that row. If all Personal Information inputs are lumped together the Form block should have the class "lazy-inputs" added to it to help with formatting, otherwise they'll appear on the same row.

-   Country Select

    -   Form Class: simple\_country\_select

        -   To hide by default (Screenshot: [*https://d.pr/i/3eKBzc*](https://d.pr/i/3eKBzc))

-   Mobile Phone

    -   Depending on if Mobile Phone is marked as required or not required in page builder, the resulting placeholder text will automatically be updated to reflect this. (Screenshot: [*https://d.pr/i/Nkgktb*](https://d.pr/i/Nkgktb))

-   Give By Selects (Screenshot: [*https://d.pr/i/b97cDu*](https://d.pr/i/b97cDu))

    -   Form Class: give-by-select radio-to-buttons en-row-center dark-buttons pill-buttons en-form-fill-width

-   Card Expiration

    -   Form Class: payment-information give-by-card stacked-inputs

-   PayPal Select

    -   These components will only show up when "Paypal" is selected

    -   Classes: give-by-paypal

-   Check Select

    -   These components will only show up when "Check" is selected

    -   Classes: give-by-check

        -   Vantiv Checking = checking
        -   Vantiv Savings = savings

-   Submit Button

    -   The submit button is added as its own form component

    -   Form Class: en-row-center pill-buttons

    -   Optional class to make button red: red

    -   Optional class to add arrow: arrow

Pre Footer (Screenshot: [*https://d.pr/i/yyGz2g*](https://d.pr/i/yyGz2g))

-   One Column Advanced Row

    -   Column 1 Class: pre-footer

Footer (Screenshot: [*https://d.pr/i/VRlkWk*](https://d.pr/i/VRlkWk))

-   One Column Advanced Row

    -   Column 1 Class: footer

Easy Background / Form Position Adjustments

-   Any Text Component

    -   Class: background-settings

    -   Optional Classes: form-right, form-left

-   In the body of the Text component with these classes you can paste a URL. That image will cover the full background of the form page and remain fixed on scroll.
