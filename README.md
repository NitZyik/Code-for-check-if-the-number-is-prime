# Number-is-prime
<h3>check the number by dividing the number from 2 to number-1</h3>
<br>
The rule is simple: all prime number are only divisible by 1 and by itself.<br>
So I thought to divide by each number unless for 1 and itself, if the rest is 0 them itsn't a prime number<br>
<br>
<blockquote>
  public boolean isPrime(n){
    for(int i = 0; i < n; i++){
      if(i % a == 0){return false}
      else{return true}
    }
  }
</blockquote>
