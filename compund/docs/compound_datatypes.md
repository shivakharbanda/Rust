1. Arrays : Contineous groups of items
            fixed length
            length should be known at compile type
            hetrogenous


            Define : [ ]
                        comma seperated

                        let array: [u32; 3] = [1, 2, 3]

            Accessing ietms by index 
                    let first_item = array[0]

            compiler warns whgen index is known to be out of bounds


            panics or crash at run time when index is out of bounds


2. Tuples : contineous groups of items 
            fixed length

            length known at compile time 

            Homogenous . can be of differnet types

        Define a Tuple 

            Open and close ()

            let tuple : (bool, u16, u8) = (true, 2, 3)


            comma seperated list of items 
            Empty list is known as "unit"


            Use a tuple: access item by index
                            imposible to access items out of bounds

                            let first_item = tuple.0;

                            