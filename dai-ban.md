#### 1、测试spring的几种事务的传播级别：

- [x] propagation_required：测试

测试完成：无论是内层事务还是外层事务，只要其中一个出现异常，则全部回滚
