自定义云厂商，当用户使用 Mof 不支持的云厂商时，可适应自定义云厂商手动输入每月账单数据。

账单数据可以在创建成功之后，在云账号页面中进行编辑。

---


## 添加账号
=== "1.基本信息"
    !!! example "解释"
        账号名称用于展示，可以重名，建议使用不同的名称。 **可修改**

=== "2.地域"
    !!! example "解释"
        确认货币属性。

        - 中国（CNY）
        - 全球（USD）

=== "2.统计维度"
    !!! example "解释"
        系统收集所有纬度的数据，默认纬度用于统计所有云厂商的成本，不影响数据准确性

## 更新账号
=== "1.基本信息"
    !!! example "解释"
        可修改，不影响数据分析。

### 账单数据
!!! example "解释"
    编辑月账单数据。

    ![](img/zh/custom-edit.png)

## 折扣列表
!!! example "解释"
    如果用户有线下的折扣合约，并且不展示在账单数据中时，用户可以在此配置，折扣会影响到**智能账单**中的数据中。

    ![](img/zh/discount.png)

## 锁定云账号和账单
!!! example "解释"
    为了防止重复拉取账单数据时，因为某些因素的改变，如标签等，导致账单过往账单可能会被更新，引入了两个锁。

    - **账号锁**：不再拉取新的数据
    - **账单锁**：不更新指定月份的账单

    ![](img/zh/lock.png)

## 数据覆盖
!!! example "解释"
    用于覆盖某月，某个 Group 下的【应付金额】。

    ![](img/zh/override-table.png)

    ![](img/zh/override-detail.png)

## 删除云账号
删除云账号时，会删除所有成本 & 资源数据。
