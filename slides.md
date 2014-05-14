class: center, middle, invert

# eCommerce & Crowdfunding

### lessons learned implementing custom web applications<br />at the Spanish Committee for UNICEF

---

name: intro
class: cover
background-image: url(http://www.etbnews.com/wp-content/uploads/file/Unicef.jpg)
<!-- background-image: url(http://www.unicef.es/sites/www.unicef.es/files/diarrea.jpg) -->
 
## .twitter[@unicef_es]

---

name: timeline

# Drupal projects timeline

--
### 2009-2010: testing the waters

* **ecards.unicef.es**: simple eCards app for business
* **tiendaempresas.unicef.es**: eCommerce for business


--
### 2010-2011: jumping with both feet

* **www.unicef.es**: main corparate site
* **tienda.unicef.es**: new eCommerce for all customers


--
### 2012-2013: building up

* **tienda.unicef.es**: eCommerce upgrade to Drupal 7
* **meayudas.unicef.es**: crowdfunding platform

---

class: center, middle, invert

# eCommerce

---

class: center, middle, cover
background-image: url(http://tienda.unicef.es/sites/tienda.unicef.es/files/imagenes/productos/raparticular/2013-10-14/kit_1auxilio2_0.jpg)

.semitransparent[
## Inspired Gifts (Regalo Azul)

###a not-so-simple product
]

---

class: center, middle
background-image: url(/img/tienda-ra-page-crop.png)

.semitransparent[
## Lets have a look at the workflow.
]
---

background-image: url(/img/tienda-ra-page-crop.png)

---

background-image: url(/img/tienda-ra-escoger-portada.png)

---

background-image: url(/img/tienda-ra-personalizar-tarjeta.png)

---

background-image: url(/img/tienda-ra-enviar-tarjeta.png)

---

background-image: url(/img/tienda-ra-cart-checkout.png)

---

# Implementation challenges

--
* The product you are buying is not the product you are getting.

--
* Highly customizable:
  * Different products.
  * Different formats (paper and virtual cards).
  * Different front covers for the same product.
  * Personal message in both card and notification.

--
* Cart & Checkout complexity: triggers.

--
* Sending mass email. 

--
* Non trivial reporting.

---

class: center, middle, invert

# Crowdfunding

---

class: center
background-image: url(/img/meayudas-image.jpg)

--

## meayudas.unicef.es

### Getting the most out of a simple idea

---

class: center, middle
background-image: url(/img/meayudas-wireframe-home.png)

--
.semitransparent[
## Not all projects have wireframes, this one did.
]

---

class: center, middle
background-image: url(/img/meayudas-home.png)

---

class: center, middle
background-image: url(/img/meayudas-wireframe-pagina.png)

---

class: center, middle
background-image: url(/img/meayudas-pagina.png)

--
.semitransparent[
## Mobile?
]

---

class: right, bottom
background-image: url(/img/meayudas-wireframe-home-mobile.png)

---

class: center, middle
background-image: url(/img/meayudas-home-mobile.png)

---

class: right, bottom
background-image: url(/img/meayudas-wireframe-pagina-mobile.png)

---

class: center, middle
background-image: url(/img/meayudas-pagina-mobile.png)

--
.semitransparent[
## And then we added landing pages
]

---

class: center, middle
background-image: url(/img/meayudas-landing.png)

---

class: center, middle, invert

# Lessons learned

---

# Don't skip discovery.


--
* Keep It Simple (product and workflow).
* Define goals.
* Know your target audience.
* Make clear what is your product and what is not.
* Draw diagrams and wireframes.
* Define acceptance tests (and automate them).


--
### Descovery costs money.

--
### Not doing it costs more money.

---

# Build a good team.

--
### When outsourcing:

* Look for providers that know their technology.
* Ask for references, call them, meet them, buy them a meal.
* Require best practices to be defined and enforce them.
* When asking for quotes make sure you have a good brief.


--
### Outsource the muscle, keep the brains:

* Business-specific know-how is difficult to outsource.
* Do basic administration inhouse.
* Digital is coming! Build a digital team.
* No in-house developers? Consider third party auditing.


---
# Backend love.

Product launching is just the beginnig.

--
* A web needs maintenance:
  * Budget for it. Schedule it.
  * Make a plan. Will you update in 3 years? in 6?

--
* A web needs administration:
   * Don't forget you are also a user. Administration pages should be thoght and designed.
   * Think about reporting and integration with your other tools.

--
* A web needs help:
  * Use and external email gateaway.
  * Use a monitoring service.

---
# Use the right tools

**And use the tools right**.  
Using Drupal as our framework of choice, allowed us:

--
* To learn, and work with, one technology for both complex and simple projects.  

--
*<small>A good idea if you manage and develop serveral applications.</small>*

--
* To write and maintain less custom code.  

--
*<small>Custom code has a place. Learn when to use it.</small>*

--
* To have a big knowledge base and best practices available.  

--
*<small>So useful. Invaluable.</small>*

--
* To avoid lock-in.  

--
*<small>It's possible to change providers, but never easy. Foster good relationships.</small>*



---
class: center, middle, invert

# Thank you

## Any questions?

.left[<br><br><small>Eduardo Esclapés &lt;eesclapes@unicef.es&gt; <br>@esclapes </small>]
