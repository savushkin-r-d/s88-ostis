# ISA-88 knowledge base

Knowledge base of [ISA-88 standard](http://www.isa-88.com/) powered by [OSTIS Technology](https://github.com/ostis-dev).

## General information

The purpose of this project is to **build an ontological model of batch manufacturing enterprise standard to improve industrial control quality of such enterprises and their ability to adapt to a constantly changing environment**.

Improvements of the industrial control level assumes a significant increase in the number of automatic or automated tasks. **This, in turn, calls for automated solutions to intelligent problems, i.e. the use of artificial intelligence technologies**.

Intelligent problems to be solved in the enterprise include:
* analysis of manufacturing situation (including emergencies);
* decision-making at different levels;
* planning behaviour in difficult circumstances;
* documentation creating and maintaining;
* employees training;
* etc.

Additional information about main ideas of this project you can read here:
* [English](https://drive.google.com/drive/folders/16n6sTeduw4ehCRdiTJEYZ4sMFfhCLlOP)
* [Русский](https://drive.google.com/drive/folders/1J85E336w4gYwgp0HQUV-UIvgW2ip02XZ)

## Sections information

### Subject domain of batch manufacturing enterprises
* ### Subject domain of physical models of batch manufacturing enterprises

  The maximal class of research objects in this specification — **equipment entity**.

  Current specification has seven levels:  
  * Enterprise level — is a largest manufacturing unit, which usually means company as a whole and consists of one or more areas. In our case, we have JSC «Savushkin product» at the enterprise level.  
  * Area level — area boundaries are usually determined based on geographical approach and contains one or more sites.
  * Site level — as per ISA-88, not every part of an area will be a part of a site. Only those directly related to batch manufacturing process will be considered as a part of a site.
  * Process cell level — contains one or more train, and the order of the equipment in it called a path.
  * Units, equipment modules and control modules — lowest three levels of a physical model are discussed together, since, according to ISA-88, process cell can directly contain units, equipment modules, as well as control modules.  

  This specification describes **processes**, **procedures**, **equipment**, **control**, etc.


  ![Physical models example](readme_images/physical_models.png?raw=true)

* ### Subject domain of process models of batch manufacturing enterprises

  The maximal class of research objects in this specification — **process element**.

  This specification describes **process stage**, **process operation**, **process action**, etc.

* ### Subject domain of procedural control models of batch manufacturing enterprises

  The maximal class of research objects in this specification — **procedural elements**.

  This specification describes **process cell procedure**, **unit procedure**, **operation**, **phase**, etc.

  ![Procedural control models example](readme_images/procedural_control_models.png?raw=true)

* ### Subject domain of batch control activities
