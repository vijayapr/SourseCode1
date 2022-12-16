# SourseCode1
String sr = "I am learning java selenium and testng with 111 and 345kg *io10090";
		Pattern obja = Pattern.compile("\\d+");
		Matcher m = obja.matcher(sr);
		while(m.find())
		{
		System.out.println("the integer values in a String is "+m.group());
		}
		Pattern obj1 = Pattern.compile("a");
		Matcher mm = obj1.matcher(sr);
		int b = 0;
		while(mm.find())
		{
			b++;
			System.out.println("the integer values of String is "+mm.group());
		}
		System.out.println("the repeated value in a string a "+b);
		
		
		Pattern obj = Pattern.compile("[a-zA-z0-9]");
		Matcher mmm = obj.matcher(sr);
		int c=0;
		while(mmm.find())
		{
			c++;
			System.out.println("the count of the string all vaules are "+mmm.group());
		}
		System.out.println(c);
		
			

	}
