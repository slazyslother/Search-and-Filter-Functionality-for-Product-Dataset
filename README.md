# Search and Filter Functionality for Large Dataset

This project involves implementing a search and filter functionality for a large product dataset in an e-commerce application. Users can search for products and filter the results based on multiple criteria such as price, category, and availability. The search and filter logic is optimized for performance to handle large amounts of 
data efficiently.

<br/>

## Features

- __Search functionality__: Allows users to search for products by name or description.
- __Filtering results__: Enables filtering based on criteria such as price range, category, and availability status.
- __Optimized search and filter logic__: Ensures high performance with large datasets.
- __JSON response format__: Facilitates easy integration with frontend applications.

<br/>

## Utility Functions

- __Search Optimization__: Implements efficient search algorithms to handle large datasets.
- __Filter Logic__: Allows filtering based on multiple criteria such as price range, category, and availability.
- __Input Validation__: Validates user input for search and filter parameters to ensure data integrity.
- __Error Handling__: Provides standardized error responses for invalid requests.
- __Database Connection__: Manages the connection to the database for storing and retrieving data.

<br/>

## Data Structure

- The product dataset is structured as follows:

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id`| `int` | The name of the product.|
| `name`| `string` | A description of the product.|        
| `description`| `string` | The price of the product.|
| `price`| `float` | The stock quantity of the product.|
| `category`| `string` | A description of the product.|        
| `availability`| `string` | The price of the product.|
| `created_at`| `datetime` | The stock quantity of the product.|

<br/>
## Popular Operations

- __Full-Text Search__: Use algorithms like the inverted index or trie for efficient searching by name or description.
- __Range Filters__: Utilize binary search or range tree data structures for fast filtering based on price range.
- __Category Filters__: Implement hash maps or indexing techniques for quick retrieval of products by category.
- __Availability Filters__: Utilize efficient data structures like binary heaps or sorted arrays for filtering products by availability status.

<br/>

## API Reference

#### __Search Products Endpoint__: Searches for products based on the given query.

```http
GET /api/products/search
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `query`| `string` | **Required**. The search query.|


#### __Filter Products Endpoint__: Filters products based on the specified criteria.

```http
GET /api/products/filter
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `query`| `string` | **Required**. The filter query.|

<br/>

## Example Scenarios

- __Search for Products by Name__: A user wants to find products that include the term "xyz" in their name.
- __Filter Products by Price Range__: A user wants to view products priced between $a and $b.
- __Filter Products by Category__: A user wants to see all products in the "xyz" category.
- __Filter Products by Availability__: A user wants to see all products that are currently in stock.
- __Combined Filter__: A user wants to see all "xyz" products priced between $a and $b that are currently in stock.


<br/>

## Support

For any questions, issues, or feature requests, please contact slazyslother@gmail.com

