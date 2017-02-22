
<pre>
# typescript_note
<h1>typescript 学习笔记</h1>
<h2>字符串属性</h2>
<h3>多行字符串</h3>
`aaa
bbb
ccc`
<h3>字符串模板</h3>
`i am ${myName}`

<h2>参数新特性</h2>
  TypeScript-参数类型 
	   function(a:string,b:number,c:boolean){} 
  TypeScript-参数默认值  
	    function(a:string,b:number,c:boolean = "yoyo"){} 
  TypeScript-可选参数 
	  function(a,b?){}
 
<h2> 函数新特性 </h2>
 
 TypeScript-Rest and Spread操作符  
      function a(...args){}
  TypeScript-generator函数 
	   function* dosomething(){
		    yeild
		 }
		 var func1 = dosomething();
		 func1.next();
 TypeScript-析构表达式 
    {a,b} = {a:xx,b:yy}
		[a,b] = [1,2]
  <h2> 表达式与循环 </h2>
 TypeScript-箭头表达式  
    ()=>{}.    args =>{ return a}
 TypeScript-for of循环 (07:16)
    for (a of Obj)
  
    for (a in Obj)
<h2>面向对象特性</h2> 
  TypeScript-类 
	 class clazz{
	   private name;
		 protected age;
		 public weight;
	 }
  TypeScript-泛型 
	  <T>
 TypeScript-接口 
   interface
 TypeScript-模块 
   import 
	 export
 TypeScript-注解 
   @
 TypeScript-类型定义文件 
   .d.ts 
 </pre>
