


Steps   
1. Backend
   1. `app/controllers/oos_controller.rb` 
      1. return recommendation hits w/ sku information 
   2. `app/controllers/internal/catalog_skus_controller.rb`: 
      1. update addSku(product_id) to addSku(...product_id)
   3. Add `lib` class to hold the hard-coded data from product
   4. Tests
2. Front End
   1. `OutOfStockModal` update design (tbd)
      1. add new action to add skus to a location and return the sku information $store
      2. quantities helper to inline amounts
