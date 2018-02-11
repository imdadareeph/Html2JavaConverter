## Welcome to html2javaconverter GitHub Pages

view the following file (https://github.com/imdadareeph/Html2JavaConverter/edit/master/README.md) to know more.


### Markdown

below is a sample code : 

```markdown

if(E.nodeName().equals("#text")){
        	String text=E.attr("text").replace(" ", "");
        	if(text.isEmpty() ||text.contains("\r\n")){
        		String text2=text.replaceAll("\r\n", "");
        		if(text2.length()>0){
        			System.out.println(s1+ "writer.write(\""+ text2+ "\");");
        		}else{
        			
        		}
        		return;
        	}else{
        		System.out.println(s1+ "writer.write(\""+ E.attr("text")+ "\");");
        	}
        	
        }
        

```
```markdown

# Change the file name in below code

File input=new File("/Users/imdadareeph/Documents/dev/eclipse/workspaces/multi/html2java/src/com/test/htmlfile.html");
		try {
			org.jsoup.nodes.Document document=Jsoup.parse(input, "UTF-8", "http://example.com");
			Html2JavaConverter.callThis(document.getAllElements().get(0), " ", "  ");
			
		} catch (IOException e) {
			
			e.printStackTrace();
		}
    
## and run Html2JavaConverter.java file
### Remember to put your html code thhat you want to convert to java in the .html file


### Support or Contact

email at imdadareeph@gmail.com for more info
