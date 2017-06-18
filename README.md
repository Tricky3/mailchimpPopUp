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

* [MailChimp Goal](http://kb.mailchimp.com/integrations/other-integrations/integrate-goal-with-mailchimp)-aware (if Goal is enabled and user / pixel is activated, popup will not show)

* Integrated Google Analytics Event-tracking for the following Actions:
  * "Displayed"
  * "ClosedWithoutSignup"
  * "FormSubmitted"
  * "Success"
  * "Error"

* Optional Facebook Conversion tracking

* User setting to toggle between successful submission response actions:
  * Standard server message
  * Custom callback, e.g. for incentivisation via [Discount Code](http://docs.shopify.com/manual/your-store/discounts) delivery<sup>*</sup>

<sub><sup>_(*) Note MailChimp requires double/confirmed opt-in so you may not actually want to deliver the code at this point_</sup></sub>

### License

Copyright (c) 'now' Tricky3

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
