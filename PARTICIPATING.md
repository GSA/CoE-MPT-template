# CoE MPP
## Participating

Before you can be awarded anything under the TTS MPP you'll need to request a DUNS number and register on SAM.gov.

## Confirm your UEI/DUNS number

Start by [obtaining a UEI number](https://interact.gsa.gov/blog/entity-validation-services-frequently-asked-questions-faqs) through the GSA website or [looking up your DUNS number](http://www.dnb.com/duns-number/lookup.html) on the Dun & Bradstreet website. If you've worked with the government in the past, you may already have one or the other.

### Obtaining a UEI number

If you don't yet have a UEI number, you can [find more information here](https://interact.gsa.gov/blog/entity-validation-services-frequently-asked-questions-faqs) or look out for instructions that will replace this sentence once they are available.

### Obtaining a DUNS number

If you don't yet have a DUNS number, you can start by [creating a Dun & Bradstreet business profile](https://www.dandb.com/product/companyupdate/companyupdateHome?execution=e10s1). You will need to use a browser other than Google Chrome, as the Dun & Bradstreet website does not currently support it. Once you've created a business profile, your DUNS number (and marketing materials, see below) will be sent to the contact information you specify within 30 days after your profile is created.

Please be aware that "as a result of obtaining a DUNS number, you *will* be included on D&B's marketing list that is sold to other companies. If you do not want your name/entity included on this marketing list, you must contact D&B to request removal." ([source](https://fsd.gov/fsd-gov/answer.do?sysparm_kbid=4dd0e67e6f585100211956532e3ee43a&sysparm_search=duns)) It is [an issue we're aware of](https://github.com/18F/micropurchase/issues/1090) and unable to resolve at the moment.

## Register on SAM.gov

Once you have your UEI or DUNS number, visit [SAM.gov](https://www.sam.gov) and create an individual account. The process is demonstrated in the video, below. Note that while registration physically takes about an hour, it can actually take **about a day or two** for the your application to be processed and for your information to propagate across various systems.

[![An overview of the SAM.gov registration process.](http://img.youtube.com/vi/YHq9KAdBI6A/0.jpg)](http://www.youtube.com/watch?v=YHq9KAdBI6A "Registering in SAM.gov")

*[An overview of the SAM.gov registration process](http://www.youtube.com/watch?v=YHq9KAdBI6A). We recommend playing it at half speed.*

Be sure to link your UEI or DUNS number with your SAM.gov profile.

## Submit a response

To submit a response, simply find an open auction by visiting the CoE MPP repository and browsing the Issues. Once you've identified an auction on which you'd like to bid, follow the instructions regarding submitting your response and you're part of the program! Good luck and we look forward to working with you!

## Getting paid

We give contractors the flexibility to choose the payment processor that works best for them. All we need is a place to enter our credit card information (Payment URL).

To specify or update your Payment URL, simply provide it when requested. We'll issue payment through your Payment URL when you win an auction and meet its Definition of Done or acceptance criteria before the delivery deadline. Please note that if you use a payment processor that charges us a fee, that fee will be deducted from the award amount (ie, we won't pay that fee on top of what we've awarded you through the auction).

PS: One payment processor we've seen used is [Stripe](https://stripe.com/docs/checkout/tutorial). Stripe is simple to setup, and doesn't charge a fee for those issuing payment. What's more, a contractor that has worked with cloud.gov actually wrote an open source app to [deploy a Stripe payment form via Heroku](https://github.com/cwarden/pay).
