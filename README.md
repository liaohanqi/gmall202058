# gmall202058

#20200508  更新了哪哪哪方面的代码，实现了什么的功能

#小王新增了一行代码，实现了什么什么的功能

#dev        是生产人员日常开发的地方     
#master     是用来过渡的。dev需要提交时，maseter先从git那里pull下来，保证自己与git是同步最新的
#           然后dev与maseter进行合并（merge）代码
#           最后，由master进行代码的最终提交


定义：dev        是生产人员日常开发的地方     
      master     是用来过渡的。dev和git的中间地带
      git        是大家共享代码的地方      
过程：首先，dev环境下，完成代码后，需要提交到dev的本地仓库；
      第二,maseter从git那里pull下来当前最新代码，确保自己与git是同步最新的
      第三，master环境下，dev（右键merge）与maseter进行合并（merge）代码,需要手动确认
      第四，maseter环境下，push代码到git上
注意：如果遇到代码不妥，可以使用revert进行重置


如果遇到代码不妥，则使用revert进行重置