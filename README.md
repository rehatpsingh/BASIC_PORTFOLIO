# bootstrap-form-validation
Validating forms found on your website is one of the most critical elements of gathering information from your site's visitors. Here's an easy way to validate forms using Bootstrap. Validation is one of the biggest priorities for your website's forms. 

## Tutorial		  
For detailed instruction's, view Solodev's [How to Validate Forms with Bootstrap](https://www.solodev.com/blog/web-design/how-to-validate-forms-with-bootstrap.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/bcxhmhd7/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="footer-form padding-top-xl padding-bottom-xl" aria-label="Contact Form">
  <div class="wrapper">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 section5 text-center">
          <h2 class="h1 font-w400">Build Your Next Amazing Web Experience</h2>
          <p class="margin-top-m margin-bottom-m">Create without limits. Solodev puts the power back in your hands – so you can build websites with total design freedom. No coding on this mission. Solodev lets you build custom web experiences that connect with your visitors – all without relying on IT.</p>
        </div>
      </div>          
      <div class="row">
        <div class="col-lg-8 col-lg-offset-2 col-md-10 col-md-offset-1">
		
          <form name="contentForm" enctype="multipart/form-data" method="" action="" role="form" data-toggle="validator" novalidate="true">
          <div class="form schedule-assessment">
            <div class="row margin-top-l">
            <div class="form-group col-md-6">
              <label for="full_name" class="sr-only">Full Name: </label>
              <input name="full_name" id="full_name" placeholder="Full name" type="text" value="" required="required" data-error="Please enter your full name.">
              <div class="help-block with-errors"></div>
            </div><!-- close col-->  
            <div class="form-group col-md-6">
              <label for="phone_number" class="sr-only">Phone Number: </label>
              <input name="phone_number" id="phone_number" placeholder="Phone number" type="text" value="" required="required" data-error="Please enter your phone number">
              <div class="help-block with-errors"></div>
            </div><!-- close col-->
            </div><!-- close row-->

            <div class="row">
            <div class="form-group col-md-6">
              <label for="email" class="sr-only">Email Address: </label>
              <input name="email" id="email" placeholder="Email Address" type="email" value="" required="required" data-error="Please enter a valid email.">
              <div class="help-block with-errors"></div>
            </div>
            <div class="form-group col-md-6">
              <label for="select_options" class="sr-only">What service are your interested in? </label>
              <select name="select_options" required="required" data-error="Please select one option.">
              <option value="">What service are you interested in?</option>
              <option value="Web Design">Web Design</option>
              <option value="Web Support">Web Support</option>
              <option value="Digital Marketing">Digital Marketing</option>
              <option value="CMS Integration">CMS Integration</option>
              <option value="Other">Other</option>
              </select>
              <div class="help-block with-errors"></div>
            </div>
            </div><!-- close row-->
            
            <div class="row">
            <div class="form-group col-md-12">
              <div class="text-center">
              <label>Do you want to receive a digital brochure?</label>
              <div class="radio">
                <label>
                <input type="radio" name="digital_brochure" value="yes" required>
                Yes, absolutely!
                </label>
              </div>
              <div class="radio">
                <label>
                <input type="radio" name="digital_brochure" value="no" required>
                No thanks.
                </label>
              </div>
              </div>
            </div>
            </div><!-- close row-->
            <div class="form-group text-center">
            <input class="submit center-block btn btn-primary" value="Submit" type="submit">
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
</section>
```

## CSS

All required CSS is contained with bootstrap-form-validation.css


## External Resources

This tutorial includes the following third party resources.

```
<<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/1000hz-bootstrap-validator/0.11.9/validator.min.js"></script>

```

