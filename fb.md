public static List<String> fizzBuzz(final int n){
        List<String> result = new ArrayList<>(n);
        for(int i=0; i<=n; i++) {
            if(i % 15 == 0) {
                result.add("FizzBuzz");
            }else if(i % 5 == 0) {
                result.add("Fizz");
            }else if(i % 3 == 0) {
                result.add("Buzz");
            }else {
                result.add(String.valueOf(n));
            }
        }
        
        return result;
    }

