def ArrayAdditionI(arr)

  a = arr.sort.last

  for i in 1..arr.length
	c = arr.combination(i).to_a

    	for j in 0..arr.combination(i).count
          if a == c[j].inject(:+)
      		return true
    	  end
        end
    
  end
  return false     
end
   
# keep this function call here 
# to see how to enter arguments in Ruby scroll down   
ArrayAdditionI(STDIN.gets)  
