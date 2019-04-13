# Draft: Sustainable Software Engineering Manifesto
## We, the undersigned, are striving for resource-efficient software engineering practices, including the whole life cycle of software: Design, Development, Deployment, Operation, Shutdown. Through this work, we have come to value ...

* **Redundant result storage** over repetitive recalculation  
    *DRY principle with regards to data: Cache (interim) results instead of recalculating them repeatedly. Storage and caching will require less resources than CPU-intensive calculations. Example: Rainbow tables over trying to guess hashes*
     
* **Dynamic scaling** over pure performance  
*Instead of providing pure performance for all times, react dynamically to changing demands.*   

* **Horizotal scaling** over vertical scaling  
*Rather use lots of small hosts than one huge oversized instance. Small hosts can be shut down. The big machine cannot be made small again*  

* **Balanced quality goals** over 100% quality ideology  
*Example: Image compression over huge, high-resolution, loss-less images, which increase storage needs, transfer time, processing...*  

* **Slim software** over feature creep  
*The bigger a piece of software, the more resources it will require. See https://www.umweltbundesamt.de/sites/default/files/medien/1410/publikationen/2018-12-12_texte_105-2018_ressourceneffiziente-software_0.pdf*  

* **Modern collaboration** over collocation  
*We don't need to travel alot anymore in order to work together. Modern collaboration tools provide all we need to create a next-to-each-other situation*  
  
That is, while there is value in the items on the right, we value the items on the left more.
