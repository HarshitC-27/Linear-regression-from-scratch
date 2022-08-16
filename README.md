# Linear-regression-from-scratch

## Approximation
<img width="129" alt="Screenshot 2022-08-16 at 8 36 40 PM" src="https://user-images.githubusercontent.com/98644005/184915655-7e0c1653-071d-41bf-8217-4dbb391e5122.png">

#### where w is the weights(slope) and b is the bias(shift along the y-axis)

## Cost function
<img width="427" alt="image" src="https://user-images.githubusercontent.com/98644005/184915865-79b84a86-1f27-4a84-a417-493b67ae6b91.png">
<img width="525" alt="Screenshot 2022-08-16 at 8 37 09 PM" src="https://user-images.githubusercontent.com/98644005/184915969-a69b06d1-81e4-49fe-85c3-fc07819fdacf.png">

## Gradient Descent
#### iterative method to get to the minimum
#### steepest descent -> go in -ve direction of the gradient till we reach the minimum

## Update Rules
### w = w - αdw
### b = b - αdb
<img width="889" alt="Screenshot 2022-08-16 at 8 37 59 PM" src="https://user-images.githubusercontent.com/98644005/184916488-50bc5aeb-a6b4-4262-aee7-ac6ec9e247d8.png">

## Learning rate
#### learning rate defines how far we go in each iteration
#### use a smaller learning rate to improve the efficiency of the algorithm

## approach
* used sklearn to generate random datasets to be used using make_regression
* initialised parameters n_samples and n_features to X.shape, also put weights and bias to zero
* compute the gradients
* update the parameters
* used matplotlib to plot the data and tha approximated line
<img width="638" alt="Screenshot 2022-08-16 at 9 16 59 PM" src="https://user-images.githubusercontent.com/98644005/184922799-2d7ecd7b-211c-4f75-85ac-ea3e43351525.png">
