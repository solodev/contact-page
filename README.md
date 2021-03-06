# contact-page
Forms are key parts of Contact Us pages. However, a form may not be enough by itself. Supplementing the contact form with direct contact information such as e-mail addresses and phone numbers will help people reach you directly when they have a question.

## Tutorial
For detailed instruction's, view Solodev's [How to Create an Efficient Contact Us Section](https://www.solodev.com/blog/web-design/how-to-create-an-efficient-contact-us-section.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/93rukcdb/).

## HTML
The tutorial contains the following basic HTML markup.

```
 div class="col-md-12">
        <div class="ct-article">
          <h1 class="mb-2">
            Contact Us
          </h1>
          <hr>
          <div class="contact-section mt-4">
            <div class="row contact-fields">
   
              <!-- Contact Info -->
              <div class="col-sm-6 col-md-3 contact-info">
                <div class="ct-navigation-panel">
                  <h4 class="h2 ct-navigation__title">
                    LunarXP
                  </h4>
                  <div class="ct-contact__panel">
                    <h5 class="ct-contact__title">
                      Connect With LUNARXP
                    </h5>
                    <p>
                      We believe that the future of mankind lies beyond earth and in the stars. Together, we can make a better tomorrow for all of us. It starts with one small step.
                    </p>
                    <ul class="ct-list-contact list-unstyled">
                      <li>
                        <i class="fa fa-phone" aria-hidden="true"></i>Call us: <a href="tel:1234567890">123.456.7890</a>
                      </li>
                      <li>
                        <i class="fa fa-envelope" aria-hidden="true"></i>Email us: <a href="mailto:info@lunarxp.com">info@lunarxp.com</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
   
              <div class="col-sm-12 col-md-9 column">
                <form>
                  <div class="row">
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">First Name *</label>
                      <input class="form-control" placeholder="First Name *" type="text">
                    </div>
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">Last Name *</label>
                      <input class="form-control" placeholder="Last Name *" type="text">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">Title *</label>
                      <input class="form-control" placeholder="Title *" type="text">
                    </div>
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">Company *</label>
                      <input class="form-control" placeholder="Company *" type="text">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-5 form-group">
                      <label class="sr-only">City *</label>
                      <input class="form-control" placeholder="City *" type="text">
                    </div>
                    <div class="col-sm-3 form-group">
                      <label class="sr-only">State *</label>
                      <select class="form-control">
                        <option disabled="disabled" selected="selected">
                          State *
                        </option>
                        <option>
                          Alabama
                        </option>
                        <option>
                          Alaska
                        </option>
                        <option>
                          Arizona
                        </option>
                        <option>
                          Arkansas
                        </option>
                        <option>
                          California
                        </option>
                        <option>
                          Colorado
                        </option>
                        <option>
                          Connecticut
                        </option>
                        <option>
                          Delaware
                        </option>
                        <option>
                          District Of Columbia
                        </option>
                        <option>
                          Florida
                        </option>
                        <option>
                          Georgia
                        </option>
                        <option>
                          Hawaii
                        </option>
                        <option>
                          Idaho
                        </option>
                        <option>
                          Illinois
                        </option>
                        <option>
                          Indiana
                        </option>
                        <option>
                          Iowa
                        </option>
                        <option>
                          Kansas
                        </option>
                        <option>
                          Kentucky
                        </option>
                        <option>
                          Louisiana
                        </option>
                        <option>
                          Maine
                        </option>
                        <option>
                          Maryland
                        </option>
                        <option>
                          Massachusetts
                        </option>
                        <option>
                          Michigan
                        </option>
                        <option>
                          Minnesota
                        </option>
                        <option>
                          Mississippi
                        </option>
                        <option>
                          Missouri
                        </option>
                        <option>
                          Montana
                        </option>
                        <option>
                          Nebraska
                        </option>
                        <option>
                          Nevada
                        </option>
                        <option>
                          New Hampshire
                        </option>
                        <option>
                          New Jersey
                        </option>
                        <option>
                          New Mexico
                        </option>
                        <option>
                          New York
                        </option>
                        <option>
                          North Carolina
                        </option>
                        <option>
                          North Dakota
                        </option>
                        <option>
                          Ohio
                        </option>
                        <option>
                          Oklahoma
                        </option>
                        <option>
                          Oregon
                        </option>
                        <option>
                          Pennsylvania
                        </option>
                        <option>
                          Puerto Rico
                        </option>
                        <option>
                          Rhode Island
                        </option>
                        <option>
                          South Carolina
                        </option>
                        <option>
                          South Dakota
                        </option>
                        <option>
                          Tennessee
                        </option>
                        <option>
                          Texas
                        </option>
                        <option>
                          Utah
                        </option>
                        <option>
                          Vermont
                        </option>
                        <option>
                          Virginia
                        </option>
                        <option>
                          Washington
                        </option>
                        <option>
                          West Virginia
                        </option>
                        <option>
                          Wisconsin
                        </option>
                        <option>
                          Wyoming
                        </option>
                      </select>
                    </div>
                    <div class="col-sm-4 form-group">
                      <label class="sr-only">Zip *</label>
                      <input class="form-control" placeholder="Zip *" type="text">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">Email *</label>
                      <input class="form-control" placeholder="Email *" type="email">
                    </div>
                    <div class="col-sm-6 form-group">
                      <label class="sr-only">Phone *</label>
                      <input class="form-control" placeholder="Phone *" type="text">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-12 form-group">
                      <label class="sr-only">Your Message</label>
                      <textarea rows="7" class="form-control" placeholder="Type your message here" cols="10"></textarea>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-12 form-group">
                      <input class="btn btn-lg" type="submit">
                    </div>
                  </div>
                </form>
              </div><!-- column -->
            </div>
          </div>
        </div>
      </div>      
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css?family=Oswald&display=swap" rel="stylesheet">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```