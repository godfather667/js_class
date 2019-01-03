**JS-CLASS**
# Introduction
This is a class version using *Class Struture and other ES6 Feature*.

It's purpose was to display a dataset on the console. 

The Data Store was implemented with maps in constant objects:
~~~~~~~~~~~~~~~~~~~~~~~~~javascript
  // Data Store
  const Parks = {
      name: ['Green', 'National', 'Oak'],
      numbTrees: [800, 1400, 760],
      parkArea: [2, 1, 1],
      yearBuilt: [1947, 1950, 1935]
  };

  const Streets = {
      name: ['Ocean Avenue', 'Evergreen Street', '4th Street', 'Sunset Boulevard'],
      size: ['big', 'small', 'normal', 'huge'],
      yearBuilt: [1999, 2008, 2015, 1982],
      length: [2.5, .75, 1.5, 5.25]
  };
~~~~~~~~~~~~~~~~~~~~~~~~~~
Using the initial data store, the project was compute and display to infromation is a prescribed format.

Ths resulting result is shown below:

![Figure [Class Version]:Class version](console_log.png)