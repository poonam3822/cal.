# cal.
module calculator {
	main () {
		console.out.println(addition (1, 5)); //output -> 6 
		console.out.println(subtract (4, 2)); //output -> 2
		console.out.println(division (4, 2)); //output -> 2
		console.out.println(multiplication (4, 2)); //output -> 8
		} 
	
	private Int addition (Int num, Int num2) {
		return num + num2;
		}
	
	private Int subtract (Int num, Int num2) { 
		return num - num2; 
		}
	
	private Int division (Int num, Int num2) { 
		return num / num2;
		}
	
	private Int multiplication (Int num, Int num2){
		return num * num2;
}
