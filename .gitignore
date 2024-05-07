public class GrandFather {

	String name;
	String property;
	String physicalAppearance;
	
    public GrandFather(String name, String property, String physicalAppearance) {
        this.name = name;
        this.property = property;
        this.physicalAppearance = physicalAppearance;
    }

    public String getName() {
        return name;
    }

    public String getProperty() {
        return property;
    }

    public String getPhysicalAppearance() {
        return physicalAppearance;
    }
	        
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		 GrandFather g = new GrandFather("chad", " Farm", “ Fit");
	        System.out.println("Grandfather:");
	        System.out.println("Name: " + g.getName());
	        System.out.println("Property: " + g.getProperty());
	        System.out.println("Physical Appearance: " + g.getPhysicalAppearance());
	}

}

public class Father extends GrandFather {

	public Father(String name, String property, String physicalAppearance) {
        super(name, property, physicalAppearance);
    }

    @Override
    public String getName() {
        return super.getName();
    }

    @Override
    public String getProperty() {
        return super.getProperty();
    }

    @Override
    public String getPhysicalAppearance() {
        return super.getPhysicalAppearance();
    }
    
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		 Father father = new Father("Seth", " Car", "old");
	        System.out.println("Father:");
	        System.out.println("Name: " + father.getName());
	        System.out.println("Property: " + father.getProperty());
	        System.out.println("Physical Appearance: " + father.getPhysicalAppearance());
	}

}

public class Son extends Father{
	
	public Son(String name, String property, String physicalAppearance) {
        super(name, property, physicalAppearance);
    }

    @Override
    public String getName() {
        return super.getName();
    }

    @Override
    public String getProperty() {
        return super.getProperty();
    }

    @Override
    public String getPhysicalAppearance() {
        return super.getPhysicalAppearance();
    }

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		 Son son = new Son("ben", "Toys", "Small,cute");
	        System.out.println("Son:");
	        System.out.println("Name: " + son.getName());
	        System.out.println("Property: " + son.getProperty());
	        System.out.println("Physical Appearance: " + son.getPhysicalAppearance());
	        
	    }
	}
