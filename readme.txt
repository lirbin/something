It("should do something, if it can", func() {
    if !someCondition {
        Skip("special condition wasn't met")
    }

    // assertions go here
    //条件满足时，会跳过该测试用例
})
