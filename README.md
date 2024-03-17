- Period : Apr.5.2020 ~ Jul.30.2020
- You can visit our website to see the data visualization. [click!](https://rgbrand.net/)

## **Why did we start the project?**

- We want analysis the color marketing associated with psychology.
- Many companies used the logo with color to recognize many people. That means colors have a great influence on people's perceptions.
- So, what is the feeling that people perceive according to color?
- We analyzed logo color and adjective, We can help prospective founders and marketers to choose logo color.

## **Analysis Process Description**

**1. Data Collection**

- We crawled logos, brand names, and corporate information for representative multinational companies, venture companies, and large domestic companies(Korean).
- Multinational companies and venture companies were crawled up to the top 100 respectively. And large domestic companies were top 200.

**2. Extract Logo color**

- Using the K-means clustering technique, R, G, and B values of representative colors are extracted from corporate logo images.

**3. color and adjective matching**

- We assigned the extracted corporate logo RGB value to the closest color to Kobayashi Color Scale and then compared the distance with the adjective of Kobayashi word image scale.
    - Kobayashi scale
    
    ![https://user-images.githubusercontent.com/102137580/161342749-8636d61d-4bda-4897-90bd-5840e77f1350.png](https://user-images.githubusercontent.com/102137580/161342749-8636d61d-4bda-4897-90bd-5840e77f1350.png)
    
- We calculated the adjective with the closest distance for each company and removed it if the distance from the adjective was 40 or more.

## **What I felt.**

- At this time, I barely knew much about machine learning. So all I could do was do simple tasks such as preprocessing, making presentation deck, and implementing simple code. But I did my best and worked hard, and I studied by myself to understand techniques like K-means. I learned a lot from this project and I believe that my growth was probably the largest among my team members.


