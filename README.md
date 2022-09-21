# Shapley-Clusters
Simple Data Visulization and Exploratory Data Analysis of the Shapley Galaxy dataset using Python libraries such as numpy, pandas, matplotlib, seaborn and astropy.


The Shapley Supercluster or Shapley Concentration (SCl 124) is the largest concentration of galaxies in our nearby universe that forms a gravitationally interacting unit, thereby pulling itself together instead of expanding with the universe. It appears as a striking overdensity in the distribution of galaxies in the constellation of Centaurus. It is 650 million light-years away.



The dataset has the following columns:

- R.A. = Right ascension: Coordinate in the sky similar to longitude on Earth, 0 to 360 degrees
- Dec. = Declination: Coordinate in the sky similar to latitude on Earth, -90 to +90 degrees  
- Mag = Magnitude: An inverted logarithmic measure of galaxy brightness in the optical band.  A Mag=17 galaxy is 100-times fainter than a Mag=12 galaxy.  Value is         missing for some galaxies.
- V = Velocity: Speed of the galaxy moving away from Earth, after various corrections are applied
- SigV = Sigma of velocity: Heteroscedastic measurement error known for each individual velocity mesurement




###Using Astronomical Coordinate System the galaxies are plotted against Right ascension and Declination, which in result shows their position in the sky.




![image](https://user-images.githubusercontent.com/72545572/191368439-75dc5a2f-650c-4fd1-bf2c-15cf81ccaa93.png)


###To map the location of galaxy, we need to plot the cartesian space coordinate from the equatorial coordinate. This one formulated from the galactic coordinate, known distance, galactic longitude, and galactic latitude. Then we calculate the redshift and distance of the galaxies and add their respective columns in the existing dataframe. 


###After we know the cartesian coordinate of galaxies, we could plot it in space. Zero indicates our galaxy (exactly our sun, which is negligible distance in mpc scale).


![image](https://user-images.githubusercontent.com/72545572/191579973-d98ff9b3-1662-416d-b503-564df41c466c.png)





![image](https://user-images.githubusercontent.com/72545572/191580342-43670c65-10aa-4205-87bc-91d31b3793d4.png)





![image](https://user-images.githubusercontent.com/72545572/191580437-b92f8777-4654-4ba8-8682-a099b7b23ca9.png)







![image](https://user-images.githubusercontent.com/72545572/191580505-04eb8845-51ee-48e4-935c-5c06e4be78b2.png)





###Redshift and Distance Distrubution


![image](https://user-images.githubusercontent.com/72545572/191580664-1b6b74d2-6b32-402f-96fc-8a10645ab5fd.png)





![image](https://user-images.githubusercontent.com/72545572/191580762-74493a4d-48fe-420a-a4bb-16b037cf81db.png)










