# Project Licences

Whenever you create a repository on github, you could always add a LICENCE.md file declaring the licence type for that repo.

If you havn't so, you can always create one by clicking `Create new file`, then type `LICENCE` in the file name, 
after that a button should come out on the right to let you choose a licence temmplate.

# Open Source vs Shared Source

Generally speaking, Open Source means you make the code available and allows others to redistribute it for profit.

If in the case you don't want others to gain profit just by adopting your code, you are actually doing Shared Source instead.
I.e. you expect interested user to come and negotiate to pay a price for use. Which in essence is similar to when you are
buying software products to use (*Remember, you buy the LICENCE from M$ Office*).

# Types of Licences

Some common open source licences are explained below:

***Permissive Licence*** means it only requires that you include the license text if you redistribute.

## BSD

This is a common permissive licence that will maximize the popularity of your code. People can use your code freely even in
closed-source or commerical projects. They just have to include the original copyright and license.

## MIT 

A permissive licence which bascially is the most populared one on github. It is almost the same as BSD licence.

Similiary of BSD & MIT:

* Permits use
* Permits redistribution
* Permits redistribution with modification
* Provision to retain the copyright notice and warranty disclaimer

In addition the MIT license also explicitly allows:

* merging
* publishing
* sublicensing
* selling

Although these freedoms seem to be implied by BSD, it does not allow sublicensing:

* Sublicensing means adding another license that implies restriction (e.g. GPL). You cannot add GPL to your code under BSD!

At times, the differences between MIT & BSD are marginal and could be confusing. Therefore the easier way is to use MIT if
you are new to licensing issue.

## GPL

This open source licence forces all the user of it to make their code open source as well. 

For example, if a company's project code has used your code as part of their's, GPL forces them to make their WHOLE 
source code available to public.

Clearly, this is a very strict requirement and not very welcomed in the commercial world, where company tends to keep
their code private or in-house.

But, it is at the same time very difficult to prove if some commerical product uses a GPL code. How can you know how someone's
code looks like if it is private?

# References
1. [What are the essential differences between BSD and MIT licences?](https://opensource.stackexchange.com/questions/217/what-are-the-essential-differences-between-bsd-and-mit-licences)
