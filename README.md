# List of Automated Testing (TDD/BDD/ATDD/SBE) Tools and Frameworks for .NET

This is a list of Automated Testing Frameworks for .NET related to methodologies and types of tests:
- Test-Driven Development (TDD)
- Behavior-Driven Development (BDD)
- Specification by Example (SBE)
- Acceptance Test-Driven Development (ATDD)
- Property-Based Testing (PBT)
- Unit \ Integration \ Acceptance \ Specification \ etc. Tests

Please feel free to suggest changes and/or new tools/frameworks.

Key:
* **Bold** — Most Popular

# Table of Contents

- [Unit Testing Frameworks](#unit-testing-frameworks)
- [Isolation Frameworks](#isolation-frameworks)
- [Acceptance Testing \ Behavior-Driven Development \ Specification by Example](#acceptance-testing-\-behavior-driven-development-\-specification-by-example)
- [Web Application Testing](#web-application-testing)
- [Web Testing](#web-testing)
- [User Interface Testing](#user-interface-testing)
- [Database Testing](#database-testing)
- [Concurrent Testing](#concurrent-testing)
- [Memory Testing](#memory-testing)
- [Mutation Testing](#mutation-testing)
- [Automated Exploratory Testing](#automated-exploratory-testing)
- [Property-Based Testing](#property-based-testing)
- [Code Coverage](#code-coverage)
- [Continuous Testing](#continuous-testing)
- [Assertion Frameworks](#assertion-frameworks)
- [Test Data Builders and Dummy Data Generators](#test-data-builders-and-dummy-data-generators)
- [Helper Libraries](#helper-libraries)
- [Miscellaneous Tools](#miscellaneous-tools)
- [Visual Studio Add-Ins](#visual-studio-add-ins)
- [Sources](#sources)

# Unit Testing Frameworks

| Framework | Licensing | Comment |
|-----------|-----------|---------|
| [csUnit](http://www.csunit.org/) | Free and open source | Discontinued
| [EMTF](https://archive.is/rptLh#selection-360.0-360.7) | Free and open source | - Known as Embeddable Micro Test Framework<Br />- Discontinued
| [Expecto](https://github.com/haf/Expecto) | Free and open source | F#
| [FsUnit](http://fsprojects.github.io/FsUnit/) | Free and open source | F#
| [Fuchu](https://github.com/mausch/Fuchu) | Free and open source | F# / C# / VB.NET
| [MbUnit](https://code.google.com/p/mb-unit/) | Free and open source | Discontinued
| [MSTest](https://github.com/Microsoft/testfx) | Free and open source | - Also known as Microsoft Test Framework<br>- Part of Visual Studio
| **[NUnit](http://www.nunit.org/)** | Free and open source
| [NUnitLite](https://github.com/nunit/nunitlite) | Free and open source | Discontinued
| [Roaster](https://roaster.codeplex.com/) | Free and open source | Discontinued
| [Unquote](http://www.swensensoftware.com/unquote) | Free and open source | F#
| **[xUnit.net](http://xunit.github.io/)** | Free and open source

# Isolation Frameworks

| Framework | Comment |
|-----------|---------|
| **[FakeItEasy](http://fakeiteasy.github.io/)**
| [Foq](https://foq.codeplex.com/)
| [JustMock](http://www.telerik.com/products/mocking.aspx)
| [JustMock Lite](http://www.telerik.com/justmock/free-mocking)
| [Microsoft Fakes](https://msdn.microsoft.com/en-us/library/hh549175.aspx) | Previously known as Microsoft Moles
| **[Moq](https://github.com/Moq/moq4)**
| [NMock](http://nmock.sourceforge.net/)
| **[NSubstitute](http://nsubstitute.github.io/)**
| [NUnit.Mocks](https://www.nuget.org/packages/NUnit.Mocks/) | Discontinued
| [Rhino Mocks](https://meisinger2.wordpress.com/category/rhino-mocks/) | Discontinued
| [Typemock Isolator](http://www.typemock.com/isolator-product-page)

# Acceptance Testing \ Behavior-Driven Development \ Specification by Example

| Framework | Comment |
|-----------|---------|
| [ApprovalTests](http://approvaltests.sourceforge.net/)
| [Avignon](http://www.nolacom.com/avignon/)
| [BDDfy](http://bddfy.teststack.net/)
| [Concordion.NET](http://concordion.org/dotnet/)
| [Cucumber](https://cucumber.io/)
| [Cuke4Nuke](https://github.com/richardlawrence/Cuke4Nuke/wiki) | Discontinued
| [FitNesse](http://fitnesse.org/)
| [Gauge](http://getgauge.io/)
| [HonestCode](http://honestcode.io/)
| [LightBDD](https://github.com/Suremaker/LightBDD)
| **[Machine.Specifications](https://github.com/machine/machine.specifications)** | Also known as MSpec
| [NaturalSpec](https://github.com/forki/NaturalSpec) | Discontinued
| [NBehave](http://nbehave.org/)
| [NDecision](https://github.com/bradygaster/NDecision) | Discontinued
| [NSpec](http://nspec.org/)
| [Robot Framework](http://robotframework.org/)
| [Spec4Net](https://bitbucket.org/fthomsen/spec4net/src) | Discontinued
| **[SpecFlow](http://www.specflow.org/)**
| [SpecsFor](http://specsfor.com/)
| [Specter](http://specter.sourceforge.net/)
| [StoryQ](http://storyq.codeplex.com/) | Discontinued
| [StoryTeller](http://storyteller.github.io/)
| [SubSpec](https://subspec.codeplex.com/)
| [System.Spec](https://github.com/alexfalkowski/System.Spec)
| [TickSpec](https://github.com/fsprojects/TickSpec)
| [xBehave.net](http://xbehave.github.io/)

# Web Application Testing

| Framework | Comment |
|-----------|---------|
| [Atata](https://github.com/atata-framework/atata)
| [Canopy](http://lefthandedgoat.github.io/canopy/) | F#
| [Coypu](https://github.com/featurist/coypu)
| [FluentAutomation](https://github.com/stirno/FluentAutomation) | Discontinued
| [IeUnit](https://code.google.com/archive/p/ieunit/) | Discontinued
| [Ivonna](http://ivonna.biz/) | Discontinued
| [Netling](https://github.com/hallatore/Netling) | Load tests for web
| [NUnitAsp](http://nunitasp.sourceforge.net/) | Discontinued
| [Selenium](http://www.seleniumhq.org/)
| [Test.Automation](https://github.com/ObjectivityLtd/Test.Automation)
| [TestStack.Seleno](http://seleno.teststack.net/)
| [WatiN](https://www.nuget.org/packages/WatiN/) | Discontinued

# Web Testing

| Framework | Comment |
|-----------|---------|
| [FakeHttpContext](https://github.com/vadimzozulya/FakeHttpContext) |
| [MockHttp](https://github.com/richardszalay/mockhttp) |
| [MockingBird](https://archive.codeplex.com/?p=mockingbird) | Discontinued
| [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) |
| [Stubbery](https://github.com/markvincze/Stubbery) | API stubs

# User Interface Testing

| Framework | Comment |
|-----------|---------|
| [Microsoft Coded UI](https://msdn.microsoft.com/en-us/library/dd286726.aspx) | Part of Visual Studio
| [NUnitForms](http://nunitforms.sourceforge.net/)
| [TestStack.White](https://github.com/TestStack/White)

# Database Testing

| Framework | Comment |
|-----------|---------|
| [DbUnit.NET](http://dbunit-net.sourceforge.net/) | Discontinued
| [NDbUnit](https://github.com/NDbUnit/NDbUnit)
| [Respawn](https://github.com/jbogard/Respawn) | A small utility to help in resetting test databases to a clean state

# Concurrent Testing

| Framework | Comment |
|-----------|---------|
| [Microsoft CHESS](http://research.microsoft.com/en-us/projects/chess/)
| [ThreadTester](http://osherove.com/blog/2007/6/22/multi-threaded-unit-tests-with-osherovethreadtester.html)
| [Typemock Racer](http://www.typemock.com/typemock-racer-product-old) | Discontinued

# Memory Testing

| Framework | Comment |
|-----------|---------|
| [.NET Memory Profiler](http://memprofiler.com/) | Also known as MemProfiler
| [dotMemory Unit](https://www.jetbrains.com/dotmemory/unit/)

# Mutation Testing

| Framework | Comment |
|-----------|---------|
| [CREAM](http://galera.ii.pw.edu.pl/~adr/CREAM/) | Also known as CREAtor of Mutants
| [Nester](http://nester.sourceforge.net/)
| [NinjaTurtles](https://ninjaturtles.codeplex.com/)
| [PIT](http://pitest.org/)
| [VisualMutator](http://visualmutator.github.io/web/)

# Automated Exploratory Testing

| Framework | Comment |
|-----------|---------|
| **[Microsoft IntelliTest](https://msdn.microsoft.com/en-us/library/dn823749.aspx)** | Part of Visual Studio<br>Previously known as:<br>- [Microsoft Code Digger](https://marketplace.visualstudio.com/items?itemName=RiSEResearchinSoftwareEngineering.MicrosoftCodeDigger)<br>- [Microsoft Pex](http://research.microsoft.com/en-us/projects/pex/)<br>- [Microsoft Smart Unit Tests](http://blogs.msdn.com/b/visualstudioalm/archive/2014/11/19/introducing-smart-unit-tests.aspx)
| [Randoop.NET](https://github.com/abb-iss/Randoop.NET)

# Property-Based Testing

| Framework | Comment |
|-----------|---------|
| [FsCheck](https://fscheck.github.io/FsCheck/) | Port of [QuickCheck](https://hackage.haskell.org/package/QuickCheck)

# Code Coverage

| Framework | Comment |
|-----------|---------|
| [AxoCover](https://github.com/axodox/AxoTools) | Bases on OpenCover
| [Coverlet](https://github.com/tonerdo/coverlet)
| [dotCover](https://www.jetbrains.com/dotcover)
| [NCover](https://www.ncover.com/)
| [NCrunch](http://www.ncrunch.net/)
| [NDepend](http://www.ndepend.com/)
| [OpenCover](https://github.com/OpenCover/opencover)
| [PartCover](http://sourceforge.net/projects/partcover/) | Discontinued
| [Semantic Designs C# Test Coverage Tool](http://www.semanticdesigns.com/Products/TestCoverage/CSharpTestCoverage.html)
| [Software Verify .NET Coverage Validator](http://www.softwareverify.com/dotnet-coverage.php)
| [Squish Coco](http://www.froglogic.com/squish/coco/)
| [TestMatrix](http://submain.com/products/testmatrix.aspx)
| [Typemock Isolator Coverage](http://www.typemock.com/coverage)
| [Visual Studio Code Coverage](https://msdn.microsoft.com/en-us/library/dd537628.aspx)

# Continuous Testing

| Framework | Comment |
|-----------|---------|
| [Continuous Testing for Visual Studio 2010](https://marketplace.visualstudio.com/items?itemName=HavardS.ContinuousTestingforVisualStudio2010) | Discontinued
| [ContinuousTests](http://www.continuoustests.com/) | Formerly Mighty Moose
| [dotCover](https://www.jetbrains.com/help/dotcover/Continuous_Testing.html)
| [Giles](http://codereflection.github.io/Giles/)
| [Live Unit Testing](https://blogs.msdn.microsoft.com/visualstudio/2017/03/09/live-unit-testing-in-visual-studio-2017-enterprise/) | Part of Visual Studio
| [NCrunch](http://www.ncrunch.net/)
| [Parasoft dotTEST](https://www.parasoft.com/product/dottest/)
| [Typemock Isolator Smart Runner](http://www.typemock.com/smart-runner)

# Assertion Frameworks

| Framework | Comment |
|-----------|---------|
| [Fluent Assertions](http://www.fluentassertions.com/)
| [SharpTestEx](http://sharptestex.codeplex.com/) | Discontinued
| [Should Assertion Library](https://github.com/erichexter/Should) | Discontinued
| [Shouldly](https://github.com/shouldly/shouldly)

# Test Data Builders and Dummy Data Generators

| Framework | Comment |
|-----------|---------|
| [Any-.Net](https://github.com/andrewseward/Any-.Net) | Discontinued
| **[AutoFixture](https://github.com/AutoFixture/AutoFixture)** |
| [AutoPoco](http://autopoco.codeplex.com/) | Discontinued
| **[Bogus](https://github.com/bchavez/Bogus)** |
| [Fabricator](http://fabricator.codeplex.com/) | Discontinued
| [Faker.Net](https://github.com/slashdotdash/faker-cs) | 
| [GenFu](https://github.com/MisterJames/GenFu) |
| [Hydrator](http://hydrator.codeplex.com/) | Discontinued
| [NBuilder](https://github.com/nbuilder/nbuilder) |
| [NTestDataBuilder](https://www.nuget.org/packages/NTestDataBuilder/) | - Now TestStack.Dossier<br />- Discontinued
| [TestData](https://github.com/kiandra-it/test-data) |
| [TestDataFactory](https://github.com/titarenko/TestDataFactory) | Discontinued
| [TestDataGenerator](https://github.com/etishor/TestDataGenerator) | Discontinued
| [TestStack.Dossier](http://dossier.teststack.net/)

# Helper Libraries

| Framework | Comment |
|-----------|---------|
| [ConventionTests](http://conventiontests.teststack.net/) | Library that makes it easy to build validation rules for convention validation tests
| [Fixie](http://fixie.github.io/) | Convention for tests
| [FluentMvcTesting](http://fluentmvctesting.teststack.net/) | Type-safe tests against ASP.NET MVC Controllees

# Miscellaneous Tools

| Framework | Comment |
|-----------|---------|
| [Gallio Automation Platform](https://code.google.com/archive/p/mb-unit/) | Discontinued
| [ErrorUnit](http://errorunit.com/) | Debug C# application by automatically creating C# Unit Tests in Visual Studio that recreate the situation leading up to the error
| [KREM](https://github.com/Bitvis/krem) | Automation and test framework. Integration, regression, spec testing. Well suitable for embedded. Written in Python, but support external scripts, etc.
| [NBi](http://www.nbi.io/) | Framework to test Business Intelligence
| [Quality Gate One Studio](http://www.qgonestudio.com/site/) | Combinatorial and Model-Based Testing 
| [TestFlask](https://github.com/FatihSahin/test-flask) | Recording and mock replay framework with the ability to generate unit tests for recorded scenarios. It also provides some tools to ease scenario testing inside ASP.NET MVC apps.

# Visual Studio Add-Ins

| Framework | Comment |
|-----------|---------|
| [nMate](https://code.google.com/archive/p/nmate/) | - Unit test code generation<br />- Discontinued
| [QuickUnit Unit Test Designer](https://visualstudiogallery.msdn.microsoft.com/dd88f120-27c6-444a-beeb-3cbdad4b620c)
| **[ReSharper](https://www.jetbrains.com/resharper/features/unit_testing.html)**
| [TestDriven.Net](http://www.testdriven.net/)
| [Unit Test Boilerplate Generator](https://marketplace.visualstudio.com/items?itemName=RandomEngy.UnitTestBoilerplateGenerator)
| [Unit Test Generator](https://marketplace.visualstudio.com/items?itemName=VisualStudioALMRangers.UnitTestGenerator) | Discontinued
| [Visual T#](https://web.archive.org/web/20110227025822/http://www.prettyobjects.com/en/Products/TSharp) | Discontinued
| [WiseTester - Overcome Unit Test Failures](https://marketplace.visualstudio.com/items?itemName=WiseTester.WiseTester-OvercomeUnitTestFailures)

# Sources

* [Osherove: Tools And Frameworks for Unit Testing in .NET for 2013](http://osherove.com/blog/2013/3/16/tools-and-frameworks-for-unit-testing-in-net-and-java.html)
* [Stack Overflow: Is there any framework for .NET to populate test data?](https://stackoverflow.com/questions/1610212/is-there-any-framework-for-net-to-populate-test-data)
* [Wikipedia: List of unit testing frameworks](https://en.wikipedia.org/wiki/List_of_unit_testing_frameworks)
