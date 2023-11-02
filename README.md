In this project, let's build a **Nxt Trendz - Cart Features** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
  <img src="https://res.cloudinary.com/dwiaeepef/image/upload/v1698935297/Screenshot_2023-11-02_154343_kg3vnt.png"/>
</div>
<br/>

### Complete Instructions

<details>
<summary>Functionality added</summary>
<br/>

The app has the following functionalities

- When an unauthenticated user tries to access the **Cart** Route, then the page is navigated to **Login** Route

- Following are the features to be implemented

  - Feature 1

    - When an authenticated user tries to add the same product multiple times
      - The quantity of the product should be updated accordingly, and the count of the cart items in the header is remain same

  - Feature 2

    - The total amount and number of items in the cart is displayed in the **Cart** Route

  - Feature 3

    - In each cart item in the cart
      - When the plus icon is clicked, then the quantity of the product is incremented by one
      - When the minus icon is clicked, then the quantity of the product is decremented by one
      - When the quantity of the product is one and the minus icon is clicked, then the respective product should be removed from the cart
      - Based on the quantity of the product, the product price, and the Cart Summary, i.e the total cost should be updated accordingly

  - Feature 4

    - When an authenticated user clicks on the remove button, the cart item is removed from the cart list

  - Feature 5

    - When an authenticated user clicks on the **Remove All** button, all the cart items should be removed from the cart and [Empty Cart View](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-empty-cart-view.png) should be displayed

- The `CartContext` has an object as a value with the following properties
  - `cartList` - this key stores the cart items
  - `removeAllCartItems` - this method is used to remove all the cart items in the `cartList`
  - `addCartItem` - this method adds the cart item to the `cartList`
  - `removeCartItem` - this method removes the cart item from the `cartList`
  - `incrementCartItemQuantity` - this method increases the quantity of a product in the `cartList`
  - `decrementCartItemQuantity` - this method decreases the quantity of a product in the `cartList`

</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>
- Prime User credentials

  ```text
   username: rahul
   password: rahul@2021
  ```

- Non-Prime User credentials

  ```text
   username: raja
   password: raja@2021
  ```

</details>
