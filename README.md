# Unnecessary Introduction 
```java
import java.util.ArrayList;
import java.util.List;

class Brain <E, Q> {
    private E dumb;
    private Q smartPercentage;
    private List<String> projects = new ArrayList<>();
    private List<String> languagesAndTools = new ArrayList<>(); 

    public Brain (E dumb, Q smartPercentage) {
        this.dumb = dumb;
        this.smartPercentage = smartPercentage;

        System.out.print("It's "+dumb+" that Michael is dumb, his IQ of smartness is "+smartPercentage);
    }

    public String projects() {
        projects.add("MichaelPlatform");
        projects.add("ExternalPlatforms");

        for (String item:projects) {
            System.out.println("Project, "+item);
        }
        return "";
    }

    public List<String> languagesAndTools() {
        languagesAndTools.add("Java");
        languagesAndTools.add("Python");
        languagesAndTools.add("Docker");
        return languagesAndTools;
    }   
}
```
