# Leeee
public class hjkk {
	public static void main(String[] args)
	{
		try {
		//StringBuffer s = new StringBuffer("123456712345671234567123456712345671234567");
		StringBuffer s =new StringBuffer(args[0]);
		s.insert(7, ",");
		int i,m;
		i=0;
		m=s.length();
		System.out.println(m);		
		while(i<=m-1)
		{
			i=i+8;
			s.insert(i, ",");
			i=i+8;
			s.insert(i, ".");
		}
		s.deleteCharAt(8);
		System.out.println(s);
		}
		catch(ArrayIndexOutOfBoundsException ne)
	     {
	      System.out.println("未提供任何参数！");
	        }
	}

}
