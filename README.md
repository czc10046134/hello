# hello
Just another repository
public class Hello {  
    @RequestMapping(value="/Hello")  
    public String HelloWorld(Model model){  
        model.addAttribute("message","Hello World!!!");  
        return "HelloWorld";  
    }  
      
