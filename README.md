class MyException extends Exception
{
	public MyException(String s)
	{
		System.out.println(s);
	}
}

class Jala {
	public static void main(String[] args){
		try{
	    	  throw new MyException("Errorrr!!");
	       }
	    catch(MyException ae)
	       {
	    	   System.out.println(ae);
	       }
	    finally
	    {
	    	System.out.println("Byeee!!!!");
	    }
	}
}
