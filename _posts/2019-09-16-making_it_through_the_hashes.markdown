---
layout: post
title:      "Making it through the Hashes "
date:       2019-09-17 02:29:21 +0000
permalink:  making_it_through_the_hashes
---


Alright! So this one was a little bit of a challenge but I was able to make it through, so you can too! 

My first challenge was started off with me having to use the literal constructor to set a variable called your_hash equal to a hash with key/value pairs of my choice in the my_hash method.

```def my_hash
<<<<<<< HEAD
  hash = {"dog" => "Pluto", "cat" => "Maru"}
end```

For the second challenge I had to create a set variable called the_manifest equal to hash in the shipping_manifest method.

```def shipping_manifest 
  the_manifest = {"oil paintings" => 3, "porcelain vases" => 2, "whale bone corsets" => 5}
end ```

The third challenge wanted me to use the same shipping_manifest hash that I used in the previous challenge for the retrieval method. So for the part of the lab I had to use the [ ] hash method to look up and retuen the value of the "oil paintings" key of the shipping_manifest hash.

```def retrieval               
  shipping_manifest = {
    "whale bone corsets"=> 5,
    "porcelain vases" => 2,
    "oil paintings" => 3
  }
  
  shipping_manifest["oil paintings"]
end```

The fourth challenge once again wanted me to use the shipping_manifest hash to start in the adding method. Then I used yje { ]= method ot add the following data to the hash:

Inventory	Quantity
muskets	2
gun powder	4

Which resulted in my final hash looking like this:
```def adding
  shipping_manifest = {
    "whale bone corsets"=> 5,
    "porcelain vases" => 2,
    "oil paintings" => 3
  }

  shipping_manifest["muskets"] = 2

  shipping_manifest["gun powder"] = 4

  shipping_manifest
	end ```
	
And there you have it on how how I did my first hash!

