# Mailchimp Modal Popup Signup 
## Module for Shopify themes

__Includes:__

* Basic styles user-configurable via admin theme settings panel
  * Modal overlay background color & opacity
  * Popup background color, border color, and text-align

* Cookie-based configuration. Be as annoying as you like! Settings for:
  * Which site visit to display popup
  * Which page to display on within a visit 
  * Whether to display once or on multiple visits
  * Time on target page before popup is displayed
  * Enable / disable on mobile devices
  * URL parameters to force enable/disable popup e.g. `yoursite.com/?signup=1`

* Integrated Google Analytics Event-tracking for the following Actions:
  * "Displayed"
  * "ClosedWithoutSignup"
  * "FormSubmitted"
  * "Success"
  * "Error"

* User setting to toggle between successful submission response actions:
  * Standard server message
  * Custom callback, e.g. for incentivisation via [Discount Code](http://docs.shopify.com/manual/your-store/discounts) delivery<sup>*</sup>

<sub><sup>_(*) Note MailChimp requires double/confirmed opt-in so you may not actually want to deliver the code at this point_</sup></sub>