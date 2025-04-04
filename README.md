# Parking spaces recommendation system

## 📌 Background
There is a problem that it is difficult to find a parking space because there are many people mainly in tourist attractions.
Therefore, this project is system for finding empty spaces when users park.
Especially, it provides convenience in parking for tourists.

</br>
## 📌 Purpose & Hypothesis
#### ☑️ Affording the recommendation system for finding a empty space to park.

#### Hypothesis : The closer it is to tourist destination, the less room there is in the parking lot.

- Case 1: If user's destination is a tourist spot...
          🔹 Recommended parking lot within 1.5km radius of destination.
  
- Case 2: If user's destination is not a tourist spot...
          🔹 Recommended parking lot within 1.5km radius of destination.
             - If there is a tourist attraction near the parking lot that you inevitably recommended...
               ➡️ Added the penalty.


</br>
##  📌 Methods
- Calculate the distance between destination and parking lot using Haversine formula

- Calculate using the own formula for distribuing parking lot recommendation points. (if it is CASE 2, we added the penalty.
<img src ='https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fc4II0A%2FbtsM9ZfBwSs%2Fip13SmkEITipTooyHUKbk1%2Fimg.png'>


</br>

## 📌 Results

### ☑️ Result of Case 1
<img src = 'https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FdxKe35%2FbtsNbdp0Kzb%2F2sNoVUkK5tvb8Y67DQMxF1%2Fimg.png'>



### ☑️ Result of Case 2
<img src = 'https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FnZRZY%2FbtsNaiTnEcY%2F7nX24srKJAa0kGHTb7QGkk%2Fimg.png'>

  
