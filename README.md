# 🧪 List of Automated Testing (TDD/BDD/ATDD/SBE) Tools and Frameworks for .NET

List of Automated Testing Frameworks for .NET related to methodologies and types of tests:
- Test-Driven Development (TDD)
- Behavior-Driven Development (BDD)
- Specification by Example (SBE)
- Acceptance Test-Driven Development (ATDD)
- Property-Based Testing (PBT)
- Unit / Integration / Acceptance / Specification / etc. Tests
- Resilience Testing (Chaos-Engineering)

Please feel free to suggest changes and/or new tools/frameworks.

Key:
* **Bold** — Most Popular / Recommended

# Table of Contents

- 🧪 Unit Testing Frameworks
- 🎭 Isolation Frameworks
- 📝 Acceptance Testing / Behavior-Driven Development / Specification by Example
- 🌍 Web Application Testing
- 🕷️ Web Testing
- ☁️ Cloud Testing
- 🖱️ User Interface Testing
- 💾 Database Testing
- 🕹️ Video Game Testing
- 🚦 Concurrent Testing
- 🧠 Memory Testing
- 🏋️ Load Testing
- 🐒 Resilience Testing
- 🧟 Mutation Testing
- 🗺️ Automated Exploratory Testing
- ⚙️ Property-Based Testing
- ✅ Approval Testing
- 📊 Code Coverage
- 🔄 Continuous Testing
- ✨ Fluent Assertion Frameworks
- 🔠 Test Data Builders and Dummy Data Generators
- ⚛️ Quantum Programming
- 🚑 Helper Libraries
- 🛠️ Miscellaneous Tools
- 🧩 Visual Studio Add-Ins

# 🧪 Unit Testing Frameworks

> What are unit test frameworks and how are they used? Simply stated, they are software tools to support writing and running unit tests, including a foundation on which to build tests and the functionality to execute the tests and report their results. They are not solely tools for testing; they can also be used as development tools on a par with preprocessors and debuggers. Unit test frameworks can contribute to almost every stage of software development, including software architecture and design, code implementation and debugging, performance optimization, and quality assurance. [Paul Hamill, Unit Test Frameworks](https://www.oreilly.com/library/view/unit-test-frameworks/0596006896/ch01.html)

| Library | Comment |
|-----------|-----------
| [csUnit](http://www.csunit.org/) | *Discontinued*
| [EMTF](https://archive.is/rptLh#selection-360.0-360.7) | - *Discontinued*<br>- Known as Embeddable Micro Test Framework
| [Expecto](https://github.com/haf/Expecto)  | F#
| [FsUnit](http://fsprojects.github.io/FsUnit/) |  F#
| [Fuchu](https://github.com/mausch/Fuchu) | F# / C# / VB.NET
| [MbUnit](https://code.google.com/p/mb-unit/) | *Discontinued*
| [MSTest](https://github.com/Microsoft/testfx) | Also known as Microsoft Test Framework
| **[NUnit](http://www.nunit.org/)** | 
| [NUnitLite](https://github.com/nunit/nunitlite) | *Discontinued*
| [Roaster](https://web.archive.org/web/20150623234601/https://roaster.codeplex.com/) |  *Discontinued*
| **[TUnit](https://github.com/thomhurst/TUnit)**
| [Unquote](https://github.com/SwensenSoftware/Unquote) | F#
| **[xUnit.net](https://xunit.net/)** | 

# 🎭 Isolation Frameworks

> An isolation framework is a set of programmable APIs that makes creating fake objects much simpler, faster, and shorter than hand-coding them. [Automate Planet](https://www.automatetheplanet.com/isolation-frameworks-fundamentals)

| Library | Comment |
|-----------|---------|
| [CleanMoq](https://techhub.social/@hassanhabib/110862012527371611) | *Discontinued*, short-lived fork of Moq
| **[FakeItEasy](http://fakeiteasy.github.io/)**
| [Foq](https://github.com/fsprojects/Foq) | F#, *Discontinued*
| [JustMock](http://www.telerik.com/products/mocking.aspx) | Non-free
| [JustMock Lite](http://www.telerik.com/justmock/free-mocking)
| [Microsoft Fakes](https://docs.microsoft.com/en-us/visualstudio/test/isolating-code-under-test-with-microsoft-fakes) | Previously known as Microsoft Moles
| [Moq](https://github.com/moq/moq) | Not recommended; read https://github.com/moq/moq/issues/1372
| [NMock](http://nmock.sourceforge.net/)
| **[NSubstitute](http://nsubstitute.github.io/)**
| [NUnit.Mocks](https://www.nuget.org/packages/NUnit.Mocks/) | *Discontinued*
| [Rhino Mocks](https://meisinger2.wordpress.com/category/rhino-mocks/) | *Discontinued*
| [SimpleStubs](https://github.com/microsoft/SimpleStubs)
| [Typemock Isolator](http://www.typemock.com/isolator-product-page) | Non-free

## Mock\replace anything (static, non-virtual, etc.)

| Library | Comment |
|-----------|---------|
| [Harmony 2.0](https://harmony.pardeike.net/) | Runtime alter functionality by monkey patching methods
| [Pose](https://github.com/tonerdo/pose) | Pose allows you to replace any .NET method (including static and non-virtual) with a delegate. It is similar to Microsoft Fakes but unlike it Pose is implemented entirely in managed code (Reflection Emit API). Everything occurs at runtime and in-memory, no unmanaged Profiling APIs and no file system pollution with re-written assemblies.
| [Smocks](https://github.com/vanderkleij/Smocks) | Smocks uses some magic under the hood to mock the normally unmockable.

# 📝 Acceptance Testing / Behavior-Driven Development / Specification by Example

| Library | Comment |
|-----------|---------|
| [ApprovalTests.Net](https://github.com/approvals/ApprovalTests.Net) | *Discontinued*
| [Avignon](http://web.archive.org/web/20160711113629/http://www.nolacom.com/avignon/) | *Discontinued*
| [BDDfy](http://bddfy.teststack.net/)
| [BddPipe](https://github.com/craigrice/bddpipe)
| [BDTest](https://github.com/thomhurst/BDTest)
| [Concordion.NET](http://concordion.org/dotnet/)
| [CoreBDD](https://github.com/stevenknox/CoreBDD/)
| [Cucumber](https://cucumber.io/)
| [Cuke4Nuke](https://github.com/richardlawrence/Cuke4Nuke/wiki) | *Discontinued*
| [FitNesse](http://fitnesse.org/)
| [Gauge](https://gauge.org/)
| [HonestCode](https://github.com/honest-code) | *Discontinued*
| [LightBDD](https://github.com/Suremaker/LightBDD)
| [LoFuUnit](https://github.com/hlaueriksson/LoFuUnit)
| **[Machine.Specifications](https://github.com/machine/machine.specifications)** | Also known as MSpec
| [NaturalSpec](https://github.com/forki/NaturalSpec) | *Discontinued*
| [NBehave](https://github.com/nbehave/NBehave) | *Discontinued*
| [NDecision](https://github.com/bradygaster/NDecision) | *Discontinued*
| [NScenario](https://github.com/cezarypiatek/NScenario) |
| [NSpec](http://nspec.org/)
| [Ogooreck](https://github.com/oskardudycz/Ogooreck)
| [Reqnroll](https://reqnroll.net/) | Open-source reboot of the SpecFlow project
| [Robot Framework](http://robotframework.org/)
| [Spec4Net](https://www.nuget.org/packages/Spec4Net/) | *Discontinued*
| [SpecFlow](http://www.specflow.org/)
| [SpecsFor](http://specsfor.com/)
| [Specter](http://specter.sourceforge.net/) | *Discontinued*
| [StoryQ](https://github.com/wforney/storyq) | *Discontinued*
| [StoryTeller](http://storyteller.github.io/)
| [SubSpec](http://web.archive.org/web/20180105002238/https://subspec.codeplex.com/) | *Discontinued*
| [System.Spec](https://github.com/alexfalkowski/System.Spec) | *Discontinued*
| [TickSpec](https://github.com/fsprojects/TickSpec)
| **[Verify](https://github.com/SimonCropp/Verify)**
| [xBehave.net](https://github.com/adamralph/xbehave.net) | *Discontinued*
| [Xunit.Gherkin.Quick](https://github.com/ttutisani/Xunit.Gherkin.Quick)

# 🌍 Web Application Testing

Testing web application UI e.g. via browser engine.

| Library | Comment |
|-----------|---------|
| [Atata](https://github.com/atata-framework/atata)
| [Canopy](http://lefthandedgoat.github.io/canopy/) | F#
| [Coypu](https://github.com/featurist/coypu)
| [FluentAutomation](https://github.com/stirno/FluentAutomation) | *Discontinued*
| [IeUnit](https://code.google.com/archive/p/ieunit/) | *Discontinued*
| [Ivonna](http://web.archive.org/web/20150801175517/http://ivonna.biz/) | *Discontinued*
| [NUnitAsp](http://nunitasp.sourceforge.net/) | *Discontinued*
| **[Playwright for .NET](https://github.com/microsoft/playwright-sharp)** | - Port of [Playwright](https://playwright.dev/)<br />- Developed by Microsoft
| [Puppeteer Sharp](https://github.com/kblok/puppeteer-sharp) | - See also [Puppeteer Sharp Contributions](https://github.com/hlaueriksson/puppeteer-sharp-contrib)
| [Ranorex](https://www.ranorex.com/) | GUI testing for desktop, web and mobile applications
| [Selenium](http://www.seleniumhq.org/)
| [Squish GUI Tester](https://www.froglogic.com/squish/)
| [Test.Automation](https://github.com/ObjectivityLtd/Test.Automation)
| [TestComplete](https://smartbear.com/product/testcomplete/overview/)
| [TestLeft](https://smartbear.com/product/testleft/overview/)
| [TestStack.Seleno](http://seleno.teststack.net/)
| [WatiN](https://www.nuget.org/packages/WatiN/) | *Discontinued*

# 🕷️ Web Testing

Testing ASP.NET, HTTP, HttpClient, REST, Web Sockets, AMQP, Blazor etc.

| Library | Comment |
|-----------|---------|
| [Alba](http://jasperfx.github.io/alba/) | Utilities for ASP.Net Core web services testing
| [bUnit](https://bunit.dev/) | Blazor components testing
| [DFrame](https://github.com/Cysharp/DFrame/) | This library allows you to write distributed load test scenarios in plain C#, no needs weird gui, dsl, xml, json, yaml. In addition to HTTP/1, you can test HTTP/2, gRPC, MagicOnion, Photon, or original network transport by writing in C#.
| [FakeHttpContext](https://github.com/vadimzozulya/FakeHttpContext) | Fake context for `HttpContext.Current`
| [Flurl](https://github.com/tmenier/Flurl) | URL builder and HTTP client library.
| [HttpClient Interception](https://github.com/justeat/httpclient-interception) | Simple library to provide stub responses in tests using HttpClient.
| [Mock4Net](https://github.com/alexvictoor/mock4net) | A fluent API allows to specify the behavior of the server and hence easily stub and mock webservices and REST resources
| [MockHttp](https://github.com/richardszalay/mockhttp) | Replacement for `HttpMessageHandler`
| [MockNet](https://github.com/Theorem/MockNet) | Friendly mocking framework to unit test the System.Net.Http namespace
| [MockingBird](http://web.archive.org/web/20180412021202/https://archive.codeplex.com/?p=mockingbird) | *Discontinued*
| [My Tested ASP.NET](https://docs.mytestedasp.net/) | A fluent unit testing library for ASP.NET Core MVC 
| [PactNet](https://github.com/pact-foundation/pact-net) |  - Port of [Pact](https://pact.io/)<br />- Testing for integrating web apps, APIs and microservices
| [Stubbery](https://github.com/markvincze/Stubbery) | API stubs
| [WireMock.Net](https://github.com/WireMock-Net/WireMock.Net) | HTTP response stubbing, matchable on URL/Path, headers, cookies and body content patterns

# ☁️ Cloud Testing

| Library | Comment |
|-----------|---------|
| [AWS .NET Mock Lambda Test Tool](https://github.com/aws/aws-lambda-dotnet)
| [Azure Functions Test Fixture](https://github.com/jeffhollan/functions-test-helper)
| [Azure Resource Manager Template Toolkit (arm-ttk)](https://github.com/Azure/arm-ttk)

# 🖱️ User Interface Testing

Testing system UI (Win32, WinForms, UWP, etc.), embedded, mobile apps

| Library | Comment |
|-----------|---------|
| [Appium](https://appium.io/docs/en/) | Supports testing of Universal Windows Platform (UWP) and Classic Windows (Win32) applications
| [Coded UI](https://msdn.microsoft.com/en-us/library/dd286726.aspx) | *Discontinued*
| [FlaUI](https://github.com/Roemer/FlaUI) | Automated UI testing of Windows applications (Win32, WinForms, WPF, Store Apps)
| [NUnitForms](http://nunitforms.sourceforge.net/) | *Discontinued*
| [Ranorex](https://www.ranorex.com/) | GUI testing for desktop, web and mobile applications
| [Scrutiny](https://github.com/kaeedo/Scrutiny) | F# and C# library for testing state machines by randomly choosing available states and valid transitions. Designed for usage with UI tests.
| [Squish GUI Tester](https://www.froglogic.com/squish/) | All kinds of cross-platform desktop, mobile, embedded and web applications
| [TestComplete](https://smartbear.com/product/testcomplete/overview/) | "Ensure the quality of your application without sacrificing speed or agility with an easy-to-use, GUI test automation tool. Our AI-powered object recognition engine and script or scriptless flexibility is unmatched, letting you test every desktop, web, and mobile application with ease."
| [TestStack.White](https://github.com/TestStack/White) | *Discontinued*
| [WinAppDriver](https://github.com/Microsoft/WinAppDriver) | - Windows Application Driver<br>- Service to support Selenium-like UI Test Automation on Windows Applications<br>- Supports testing Universal Windows Platform (UWP), Windows Forms (WinForms), Windows Presentation Foundation (WPF), and Classic Windows (Win32) apps on Windows 10 PCs

# 💾 Database Testing

| Library | Comment |
|-----------|---------|
| [DbUnit.NET](http://dbunit-net.sourceforge.net/) | *Discontinued*
| [NDbUnit](https://github.com/NDbUnit/NDbUnit) | - *Discontinued*<br>- Managing database state during unit testing
| [Respawn](https://github.com/jbogard/Respawn) | A small utility to help in resetting test databases to a clean state

# 🕹️ Video Game Testing

| Library | Comment |
|-----------|---------|
| [GameDriver](https://gamedriver.io/) | 

# 🚦 Concurrent Testing

| Library | Comment |
|-----------|---------|
| [FluentAssertions.Extensions](https://github.com/Kittyfisto/FluentAssertions.Extensions)
| [Microsoft CHESS](http://research.microsoft.com/en-us/projects/chess/) | - *Discontinued*<br>- "CHESS is a tool for finding and reproducing Heisenbugs in concurrent programs. CHESS repeatedly runs a concurrent test ensuring that every run takes a different interleaving. If an interleaving results in an error, CHESS can reproduce the interleaving for improved debugging. CHESS is available for both managed and native programs."
| [Microsoft Coyote](https://microsoft.github.io/coyote/)
| [Osherove.ThreadTester](http://osherove.com/blog/2007/6/22/multi-threaded-unit-tests-with-osherovethreadtester.html) | *Discontinued*
| [Typemock Racer](http://www.typemock.com/typemock-racer-product-old) | *Discontinued*

# 🧠 Memory Testing

| Library | Comment |
|-----------|---------|
| [.NET Memory Profiler](http://memprofiler.com/) | Also known as MemProfiler
| **[dotMemory Unit](https://www.jetbrains.com/dotmemory/unit/)**

# 🏋️ Load Testing

| Library | Comment |
|-----------|---------|
| [Apache Bench](https://httpd.apache.org/docs/2.4/programs/ab.html) | Also known as `ab`
| [Apache JMeter](https://jmeter.apache.org/) |
| [Azure Load Testing](https://learn.microsoft.com/en-us/azure/load-testing/overview-what-is-azure-load-testing) |
| [BenchmarkDotNet](https://benchmarkdotnet.org/)
| [Gatling](https://gatling.io/)
| [JMEter DSL .NET](https://abstracta.github.io/jmeter-dotnet-dsl/) |
| [k6](https://k6.io/)
| [NBomber](https://nbomber.com/) |
| [Netling](https://github.com/hallatore/Netling) |
| [West Wind WebSurge](https://websurge.west-wind.com/)

# 🐒 Resilience Testing

| Library | Comment |
|-----------|---------|
| [Simmy](https://github.com/Polly-Contrib/Simmy) | Simmy is a chaos-engineering and fault-injection tool, integrating with the Polly resilience project for .NET

# 🧟 Mutation Testing

> Mutation testing (or mutation analysis or program mutation) is used to design new software tests and evaluate the quality of existing software tests. Mutation testing involves modifying a program in small ways. Each mutated version is called a mutant and tests detect and reject mutants by causing the behavior of the original version to differ from the mutant. This is called killing the mutant. Test suites are measured by the percentage of mutants that they kill. New tests can be designed to kill additional mutants. Mutants are based on well-defined mutation operators that either mimic typical programming errors (such as using the wrong operator or variable name) or force the creation of valuable tests (such as dividing each expression by zero). The purpose is to help the tester develop effective tests or locate weaknesses in the test data used for the program or in sections of the code that are seldom or never accessed during execution. Mutation testing is a form of white-box testing. [Wikipedia](https://en.wikipedia.org/wiki/Mutation_testing)

| Library | Comment |
|-----------|---------|
| [CREAM](http://galera.ii.pw.edu.pl/~adr/CREAM/) | Also known as CREAtor of Mutants
| [Fettle](https://github.com/ComparetheMarket/fettle)
| [Nester](http://nester.sourceforge.net/)
| [NinjaTurtles](http://web.archive.org/web/20171222222621/https://ninjaturtles.codeplex.com/) | *Discontinued*
| [NinjaTurtlesMutation](https://github.com/criteo/NinjaTurtlesMutation) | Fork of NinjaTurtles
| [PIT](http://pitest.org/)
| [Stryker](https://stryker-mutator.io/)
| [Testura.Mutation](https://github.com/Testura/Testura.Mutation)
| [VisualMutator](http://visualmutator.github.io/web/)

# 🗺️ Automated Exploratory Testing

> Exploratory testing is an approach to software testing that is often described as simultaneous learning, test design, and execution. It focuses on discovery and relies on the guidance of the individual tester to uncover defects that are not easily covered in the scope of other tests. [Atlassian](https://www.atlassian.com/continuous-delivery/software-testing/exploratory-testing)

| Library | Comment |
|-----------|---------|
| **[Microsoft IntelliTest](https://msdn.microsoft.com/en-us/library/dn823749.aspx)** | Part of Visual Studio<br>Previously known as:<br>- [Microsoft Code Digger](https://marketplace.visualstudio.com/items?itemName=RiSEResearchinSoftwareEngineering.MicrosoftCodeDigger)<br>- [Microsoft Pex](http://research.microsoft.com/en-us/projects/pex/)<br>- [Microsoft Smart Unit Tests](http://blogs.msdn.com/b/visualstudioalm/archive/2014/11/19/introducing-smart-unit-tests.aspx)
| [Randoop.NET](https://github.com/abb-iss/Randoop.NET)

# ⚙️ Property-Based Testing

> Property based testing relies on properties. It checks that a function, program or whatever system under test abides by a property. Most of the time, properties do not have to go into too much details about the output. They just have to check for useful characteristics that must be seen in the output. [Nicolas Dubien, Introduction to Property Based Testing](https://medium.com/criteo-engineering/introduction-to-property-based-testing-f5236229d237)

| Library | Comment |
|-----------|---------|
| [CsCheck](https://github.com/AnthonyLloyd/CsCheck)
| **[FsCheck](https://fscheck.github.io/FsCheck/)** | Port of [QuickCheck](https://hackage.haskell.org/package/QuickCheck)
| [Hedgehog](https://github.com/hedgehogqa/fsharp-hedgehog) | F# port of [Hedgehog](https://hedgehog.qa/)

# ✅ Approval Testing

| Library | Comment |
|-----------|---------|
| [ApprovalTests.Net](https://github.com/approvals/ApprovalTests.Net) | 
| [DiffEngine](https://github.com/VerifyTests/DiffEngine) | Manages launching and cleanup of diff tools. Used by ApprovalTests, Shouldly, Verify
| [Polaroider](https://wickedflame.github.io/Polaroider/) |
| [Shouldly](https://github.com/shouldly/shouldly) | See [`ShouldMatchApproved`](https://putlocker-watch-spectre-online-movie-free.readthedocs.io/en/latest/assertions/shouldMatchApproved.html)
| [Snapper](https://github.com/theramis/Snapper) |
| [Snapshooter](https://swisslife-oss.github.io/snapshooter/) | 
| [Verify](https://github.com/SimonCropp/Verify) | 

# 📊 Code Coverage

| Library | Comment |
|-----------|---------|
| [AxoCover](https://github.com/axodox/AxoTools) | Based on OpenCover
| [Coverlet](https://github.com/tonerdo/coverlet)
| **[dotCover](https://www.jetbrains.com/dotcover)**
| [Fine Code Coverage](https://marketplace.visualstudio.com/items?itemName=FortuneNgwenya.FineCodeCoverage)
| [NCover](https://www.ncover.com/)
| [NCrunch](http://www.ncrunch.net/)
| [NDepend](http://www.ndepend.com/)
| [OpenCover](https://github.com/OpenCover/opencover)
| [PartCover](http://sourceforge.net/projects/partcover/) | *Discontinued*
| [Semantic Designs C# Test Coverage Tool](http://www.semanticdesigns.com/Products/TestCoverage/CSharpTestCoverage.html)
| [Software Verify .NET Coverage Validator](http://www.softwareverify.com/dotnet-coverage.php)
| [Squish Coco](http://www.froglogic.com/squish/coco/)
| [TestMatrix](http://submain.com/products/testmatrix.aspx)
| [Typemock Isolator Coverage](http://www.typemock.com/coverage)
| [Visual Studio Code Coverage](https://msdn.microsoft.com/en-us/library/dd537628.aspx) | Part of Visual Studio

# 🔄 Continuous Testing

> Continuous testing is the process of executing automated tests as part of the software delivery pipeline to obtain immediate feedback on the business risks associated with a software release candidate. [Wikipedia](https://en.wikipedia.org/wiki/Continuous_testing)

| Library | Comment |
|-----------|---------|
| [Continuous Testing for Visual Studio 2010](https://marketplace.visualstudio.com/items?itemName=HavardS.ContinuousTestingforVisualStudio2010) | *Discontinued*
| [ContinuousTests](http://www.continuoustests.com/) | Formerly Mighty Moose
| **[dotCover](https://www.jetbrains.com/help/dotcover/Continuous_Testing.html)**
| [Giles](http://codereflection.github.io/Giles/)
| **[Live Unit Testing](https://blogs.msdn.microsoft.com/visualstudio/2017/03/09/live-unit-testing-in-visual-studio-2017-enterprise/)** | Part of Visual Studio
| [NCrunch](http://www.ncrunch.net/)
| [Parasoft dotTEST](https://www.parasoft.com/product/dottest/)
| [Typemock Isolator Smart Runner](http://www.typemock.com/smart-runner)

# ✨ Fluent Assertion Frameworks

| Library | Comment |
|-----------|---------|
| [Awesome Assertions](https://awesomeassertions.org/) | A fork of FluentAssertions controlled by the community
| [Fluent Assertions](http://www.fluentassertions.com/)
| [NFluent](http://www.n-fluent.net/)
| [NUnitEx](https://code.google.com/archive/p/nunitex/) | *Discontinued*
| [SharpTestEx](https://www.codewrecks.com/post/old/2011/03/writing-a-custom-assertion-for-sharptestex/) | *Discontinued*
| [Should Assertion Library](https://github.com/erichexter/Should) | *Discontinued*
| [Shouldly](https://github.com/shouldly/shouldly)

# 🔠 Test Data Builders and Dummy Data Generators

| Library | Comment |
|-----------|---------|
| [Any-.Net](https://github.com/andrewseward/Any-.Net) | *Discontinued*
| [AutoBogus](https://github.com/nickdodd79/AutoBogus)
| **[AutoFixture](https://github.com/AutoFixture/AutoFixture)** |
| [AutoPoco](https://www.nuget.org/packages/AutoPoco/) | *Discontinued*
| [AutoPocoIO](https://github.com/AutoPocoIO/AutoPocoIO) 
| **[Bogus](https://github.com/bchavez/Bogus)** |
| [Fabricator](https://www.nuget.org/packages/Fabricator/) | *Discontinued*
| [Faker.Net](https://github.com/slashdotdash/faker-cs) | *Discontinued*
| [GenFu](https://github.com/MisterJames/GenFu) |
| [Hydrator](https://www.nuget.org/packages/Hydrator) | *Discontinued*
| [NaughtyStrings](https://github.com/SimonCropp/NaughtyStrings) | .NET API for [Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)
| [NBuilder](https://github.com/nbuilder/nbuilder) |
| [NTestDataBuilder](https://www.nuget.org/packages/NTestDataBuilder/) | - Now TestStack.Dossier<br />- Discontinued
| [TestData](https://github.com/kiandra-it/test-data) |
| [TestDataFactory](https://github.com/titarenko/TestDataFactory) | *Discontinued*
| [TestDataGenerator](https://github.com/etishor/TestDataGenerator) | *Discontinued*
| [TestStack.Dossier](http://dossier.teststack.net/)
| [Tynamix ObjectFiller.NET](https://github.com/Tynamix/ObjectFiller.NET)

# ⚛️ Quantum Programming

| Library | Comment |
|-----------|---------|
| [Q# Test Project](https://docs.microsoft.com/en-us/azure/quantum/user-guide/testing-debugging?tabs=tabid-vs2022) |

# 🧩 Helper Libraries

| Library | Comment |
|-----------|---------|
| [AutoMoq](https://github.com/darrencauthon/AutoMoq) | Auto mocking provider for Moq, *Discontinued*
| [Automoqer](https://github.com/rbengtsson/Automoqer) | Auto mocking provider for Moq, *Discontinued*
| [ConventionTests](http://conventiontests.teststack.net/) | Library that makes it easy to build validation rules for convention validation tests
| [FakeLocalTimeZone](https://github.com/dariusz-wozniak/FakeLocalTimeZone) | Fake of system TimeZone
| [Fixie](http://fixie.github.io/) | Convention for tests
| [FluentMvcTesting](http://fluentmvctesting.teststack.net/) | Type-safe tests against ASP.NET MVC Controllers
| [MockQueryable](https://github.com/romantitov/MockQueryable) | Extensions for mocking EfCore
| [SparkyTestHelpers](https://github.com/BrianSchroer/sparky-test-helpers) | Unit test helpers for config files, ASP.NET MVC, and Moq among others
| [XMLUnit](https://www.xmlunit.org/) | Unit testing XML

# 🛠️ Miscellaneous Tools

| Library | Comment |
|-----------|---------|
| [.NET Testcontainers](https://github.com/HofmeisterAn/dotnet-testcontainers) | Library to support tests with throwaway instances of Docker containers 
| [AccidentalFish.FSharp.Validation](https://github.com/JamesRandall/AccidentalFish.FSharp.Validation) | Simple validator DSL / library for F#
| [ArchUnitNET](https://github.com/TNG/ArchUnitNET) | Library for checking the architecture of C# code
| [CheckTestOutput](https://github.com/exyi/CheckTestOutput) | A library for semi-manual tests. Run a function, manually check the output. But only if it is different than last run
| [Compare-Net-Objects](https://github.com/GregFinzer/Compare-Net-Objects) | Deep compare of any two .NET objects using reflection
| [Gallio Automation Platform](https://code.google.com/archive/p/mb-unit/) | - Common object model, runtime services and tools (such as test runners) that may be leveraged by any number of test frameworks.<br> - *Discontinued*
| [ErrorUnit](http://errorunit.com/) | Debug C# application by automatically creating C# Unit Tests in Visual Studio that recreate the situation leading up to the error
| [ExpressionToCode](https://github.com/EamonNerbonne/ExpressionToCode) | Generates valid, readable C# from an Expression Tree
| [KREM](https://github.com/Bitvis/krem) | Automation and test framework. Integration, regression, spec testing. Well suitable for embedded. Written in Python, but support external scripts, etc.
| [Microsoft.Testing.Platform](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-platform-intro) | Microsoft.Testing.Platform is a lightweight and portable alternative to VSTest for running tests in all contexts, including continuous integration (CI) pipelines, CLI, Visual Studio Test Explorer, and VS Code Text Explorer. The Microsoft.Testing.Platform is embedded directly in your test projects, and there's no other app dependencies, such as vstest.console or dotnet test needed to run your tests.
| [NBi](http://www.nbi.io/) | Framework to test Business Intelligence
| [NScenario](https://github.com/cezarypiatek/NScenario) | Library for annotating steps of test case scenarios
| [Quality Gate One Studio](http://web.archive.org/web/20180906043816/http://www.qgonestudio.com/site/) | Combinatorial and Model-Based Testing, *Discontinued*
| [Scientist.NET](https://github.com/scientistproject/Scientist.net) | A library for carefully refactoring critical paths
| [Squish Test Center](https://www.froglogic.com/testcenter/) | Aggregates test results in a central server and generates statistics
| [TestFlask](https://github.com/FatihSahin/test-flask) | Recording and mock replay framework with the ability to generate unit tests for recorded scenarios. It also provides some tools to ease scenario testing inside ASP.NET MVC apps
| [Visual Studio Test Platform](https://github.com/microsoft/vstest) | Also known as VSTest<br>The Visual Studio Test Platform is an open and extensible test platform that enables running tests, collect diagnostics data and report results. The Test Platform supports running tests written in various test frameworks, and using a pluggable adapter model. Based on user-choice, the desired test framework and its corresponding adapter can be acquired as a vsix or as NuGet package as the case may be. Adapters can be written in terms of a public API exposed by the Test Platform.
| [xRetry](https://github.com/JoshKeegan/xRetry) | Retry flickering test cases for xUnit and SpecFlow

# Visual Studio Add-Ins

| Library | Comment |
|-----------|---------|
| [GennyMcGenFace](https://marketplace.visualstudio.com/items?itemName=Armastevs.GennyMcGenFace) | Unit test generator
| [nMate](https://code.google.com/archive/p/nmate/) | - Unit test code generator<br />- *Discontinued*
| [QuickUnit Unit Test Designer](https://visualstudiogallery.msdn.microsoft.com/dd88f120-27c6-444a-beeb-3cbdad4b620c)
| **[ReSharper](https://www.jetbrains.com/resharper/features/unit_testing.html)**
| [TestDriven.Net](http://www.testdriven.net/)
| [Unit Test Boilerplate Generator](https://marketplace.visualstudio.com/items?itemName=RandomEngy.UnitTestBoilerplateGenerator)
| [Unit Test Generator](https://devblogs.microsoft.com/devops/visual-studio-unit-test-generator-is-feature-complete-v1-release-candidate-lands-2/) | *Discontinued*
| [Unitverse](https://marketplace.visualstudio.com/items?itemName=MattWhitfield.Unitverse) | Unit test generator
| [Visual T#](https://web.archive.org/web/20110227025822/http://www.prettyobjects.com/en/Products/TSharp) | *Discontinued*
| [WiseTester](https://marketplace.visualstudio.com/items?itemName=WiseTester.WiseTester-OvercomeUnitTestFailures)

# References

* [Awesome .NET: .NET Testing](https://dotnet.libhunt.com/categories/1837-testing)
* [Osherove: Tools And Frameworks for Unit Testing in .NET for 2013](http://osherove.com/blog/2013/3/16/tools-and-frameworks-for-unit-testing-in-net-and-java.html)
* [Stack Overflow: Is there any framework for .NET to populate test data?](https://stackoverflow.com/questions/1610212/is-there-any-framework-for-net-to-populate-test-data)
* [Wikipedia: List of unit testing frameworks](https://en.wikipedia.org/wiki/List_of_unit_testing_frameworks)
