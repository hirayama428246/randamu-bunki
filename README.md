# randamu-bunki
//intが乱数により５～－５まで　結果によって出力がかわる
public class Main {
 
    
	public static void main(String[] args) {
		System.out.println("数字によって変わります");
		 
		 int num = new java.util.Random().nextInt(10) - 5;
		 
		 if(num < 0){
		  System.out.println("負です");
		  
		  
		  }else if(num > 0){
		      System.out.println("正です");
		  
		  }else{
		      System.out.println("0です");
		      
		  }
		      
           }
    }
