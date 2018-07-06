**_Example of lazy singleton_**

    public class TestSingleton {
	private static TestSingleton instance; 

	public static TestSingleton getInstance() {
		if (instance == null) {
		    instance = new TestSingleton();
		}
	    return instance;
	}

	private TestSingleton() {}
	}
	

