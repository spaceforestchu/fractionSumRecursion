# fractionSumRecursion

        function fractionSum(num){
            
           if(num === 2){
               return 1/num;
           } else {
              return fractionSum(num - 1) + 1/num; 
           }
        }
        fractionSum(100);
