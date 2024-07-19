添加新老师.yml

name: 添加新老师
description: 遇到没被纳入的新老师？请在这里提交
title: "[新老师]"
labels: ["新老师"]
assignees: []

body:
  - type: input
    id: teacher_name
    attributes:
      label: 老师姓名
    validations:
      required: true
  - type: input
    id: college
    attributes:
      label: 所在学院
    validations:
      required: true
  - type: input
    id: website_link
    attributes:
      label:  `zju.edu.cn` 网页链接
      placeholder: https://xxx.zju.edu.cn/xxx
    validations:
      required: false
  - type: textarea
    id: additional_info
    attributes:
      label: 补充信息
      placeholder: 可以提供截图
    validations:
      required: false
