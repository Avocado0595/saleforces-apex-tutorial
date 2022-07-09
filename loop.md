List<Integer> nums = new List<Integer>();
Integer i = 0, max=21;

While(i<max){
    nums.add(i);
    i+=1;
}

Integer sum = 0;
i=0;
while(i<max){
    if(math.mod(i,2)==0){
        sum+=i;
        System.debug(i);
    }
    i+=1;
}

