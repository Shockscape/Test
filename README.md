  // Cost of buying something + tax

                Console.WriteLine("How much does the product cost that you are buying?");
                double productCost = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("How much is the tax in your country, percentage wise?");
                double buyTax = Convert.ToInt32(Console.ReadLine());
                double taxTotal = productCost * buyTax / 100;
                Console.WriteLine($"The tax you will pay on top of the original price is {taxTotal}.");
                double productTotal = taxTotal + productCost;
                Console.WriteLine($"The total price of the product is now {productTotal}");
