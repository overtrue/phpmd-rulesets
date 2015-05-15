# phpmd-rulesets
PHP_MD 规则

# Rules

- 循环复杂度（CyclomaticComplexity）报警级别：`15`
- 类复杂度（ExcessiveClassComplexity）报警级别：`120`
- 类最多 20 方法
- 其它内置规则


# Usage

1. 下载

    ```shell
    git clone https://github.com/overtrue/phpmd-rulesets
    ```

2. 移动到你想要移动的任何目录，或者不移动

    ```shell
    mv phpmd-rulesets YOU_PATH
    ```

3. 使用

    ```shell
    phpmd ./Foo.php text YOU_PATH/phpmd_ruleset.xml
    ```

    > phpmd语法：`phpmd` `目标文件或目录` `报告输出格式` `规则路径`
    > 报告输出格式有:`xml`,`text`,`html`

关于PHPMD，请参考官方网站：http://phpmd.org/