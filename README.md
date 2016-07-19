# PalindromeNumberOrNot

public class ReverseANumber {

	public static void main(String[]arg)
	{
		Scanner get=new Scanner(System.in);
		int input=get.nextInt();
		int a=input;
		int dumy=0;
		if(input>-10 && input<10)
		{
		System.out.println("enter two digit number");	
		}
		else
		{
		
		while(input!=0)
		{
			dumy=dumy*10;
			dumy=dumy+(input%10);
			input=input/10;
		}
		if(a==dumy)
		{
			System.out.println("Palindrome");
		}
		else
		{
			System.out.println("Not a Palindrome");
		}
	}
	}
}
