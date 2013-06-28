ZendStudio10-Config
===================

ZendStudio 10 - Configs

I have been having serious issues with imported projects in ZendStudio10 and subsequently autocomplete/building failing. 

Attached are my .project and .buildpath files for ZF2 projects for a project I know has autocomplete working correctly. You must replace the project name placeholder in the .project file.


Builds
- JavaScript Validator
- Validation
- Script Builder
 

PHP Build Path
- Included ALL
- Excluded None
 

PHP Include Path
- Source
  - Path to current project - (Likely to be missing if imported / built manually)
- Projects
  - Empty
- Librarys (defined in your buildpath)
  - PHPUnit 3.x Library (Buildpath container: com.zend.php.phpunit.CONTAINER)
  - Zend Framework 2 (Buildpath container: org.zend.php.framework.v2.CONTAINER)
