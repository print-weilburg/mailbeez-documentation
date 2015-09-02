---
# http://learn.getgrav.org/content/headers
title: Extended Customer Information
slug: extended-customer-information
# menu: Extended Customer Information
date: 26-09-2011
published: true
publish_date: 26-09-2011
# unpublish_date: 26-09-2011
# template: false
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration-status: review
    category: []
    tag: []
# added collection selector

author:
    name: admin
metadata:
    author: admin
#      description: Your page description goes here
#      keywords: HTML, CSS, XML, JavaScript
#      robots: noindex, nofollow
#      og:
#          title: The Rock
#          type: video.movie
#          url: http://www.imdb.com/title/tt0117500/
#          image: http://ia.media-imdb.com/images/rock.jpg
#  cache_enable: false
#  last_modified: true
---

This module lets you add a variety of additional customer information into your emails so that each customer will receive personalized emails that provide the impression that the mailings you send them are customized just for them, vs. an impersonal bulk mailing that goes out to a massive mailing list.

For example, in addition to displaying the customer's name in your emails, you can also display or use their date of birth, age, phone number, company name, address, fax number, newsletter subscription status, and more!

 
    {$data.customer.firstname} // firstname
    {$data.customer.lastname} // lastname
    {$data.customer.dob} // date of birth
    {$data.customer.age} // age
    {$data.customer.telephone} // phone
    {$data.customer.fax} // fax
    {$data.customer.newsletter} // newsletter 0/1
    {$data.customer.company} // company
    {$data.customer.postcode} // postcode
    {$data.customer.city} // city
    {$data.customer.state} // state
    {$data.customer.country_id} // country id
    {$data.customer.zone_id} // zone id
    {$data.customer.raw} // array with all data


**Example:** Age-dependent salutation

check the [smarty documentation](http://www.smarty.net/docsv2/en/language.function.if.tpl) for more examples of if else statements

smarty syntax

 
    {if $data.customer.age gt 30}
        above 30: hello sir, your age is {$data.customer.age} - dob: {$data.customer.dob}
    {else}
        below 31: hi there, your are is {$data.customer.age} - dob {$data.customer.dob}
    {/if}


or

visual editor tags protected from editing:

 
    [[if $data.customer.age gt 30]]
        above 30: hello sir, your age is [[$data.customer.age]] - dob: [[$data.customer.dob]]
    [[else]]
        below 31: hi there, your are is [[$data.customer.age]] - dob [[$data.customer.dob]]
    [[/if]]


Installation and configuration are fast and easy! Installation instructions are included in the download package. [Configuration Tutorial](http://www.mailbeez.com/documentation/tutorials/filterbeez-tutorials/extended-customer-information-configuration-tutorial/) for this module.
