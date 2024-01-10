A house listing schema model

```js
import { Schema, Document, mongoose, model } from 'mongoose'

export const function IListing extends Document {
  title: string;
  description: string;
  type: boolean;
  price: string;
}

export const function listingSchema = new Schema({
   title: { type: String, required: true }
   description: {type : String, required: true}
   type: { type: Boolean, required: true}
   price: { type: String, required: true}
})

Listing = mongoose.model("Listing", "listingSchema")

export default Listing;
```

* Explanation 


Find, book or rent a car — quickly and easily!
Streamline your car rental business with our effortless booking process.



