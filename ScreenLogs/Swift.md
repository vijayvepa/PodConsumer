
|Task	|Swift	|C#|
|---|---|---|
String interpolation	print("Logging is in debug mode: \(isDebug)");	Console.WriteLine("Logging is in debug mode: {0}", IsDebug);
Private field	private var isDebug: Bool!	private bool IsDebug;
Constructor	public init() {self.isDebug = false}	public Ylog() { this.IsDebug = false;} 
Method	public func setup(isDebug: Bool)	public void Setup(bool isDebug)
Print Output	print("Logging")	Console.WriteLine("Logging")
Generic Method	public func YPrint<T>(value: T)	public void YPrint<T>(T value)
Import Namespace	import YLogging	using YLogging;
Object instantiation/Global Vars	let logger = YLog()	class Global{public static YLog Logger = new YLog(); }
Method Call	logger.setup(isDebug: true)	Logger.Setup(true);
Object instantiation	let logger = YLog()	
