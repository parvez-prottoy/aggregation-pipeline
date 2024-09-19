# Learn Aggregation Pipeline

- If your users data like 100 and here is a property in isActive the question is How many users are active? <br>
  ```
  [
  {
    $match: {
      isActive:true
    }
  },
  {
    $count: 'totalActive'
  }
  ]
  ```
