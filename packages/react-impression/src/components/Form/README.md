### 示例

**行内表单**

```js
<Form>
  <FormGroup>
    <label>姓名</label>
    <Input type="text" placeholder="Jane Doe" />
  </FormGroup>
  <FormGroup>
    <label>邮箱</label>
    <Input type="text" placeholder="hello@example.com" />
  </FormGroup>
  <FormGroup>
    <Checkbox defaultChecked>记住我</Checkbox>
  </FormGroup>
  <Button theme="primary">搜索</Button>
  <Button theme="default">重置</Button>
</Form>
```

**表单示例**

```js
<Form type="horizontal">
  <FormGroup>
    <Col col="2" className="text-right">
      <FormControlLabel>邮箱:</FormControlLabel>
    </Col>
    <Col col="10">
      <Input type="text" placeholder="hello@example.com" />
    </Col>
  </FormGroup>
  <FormGroup>
    <Col col="2" className="text-right">
      <FormControlLabel>姓名:</FormControlLabel>
    </Col>
    <Col col="10">
      <Input type="password" />
    </Col>
  </FormGroup>
  <FormGroup>
    <Col col="2" className="text-right">
      <FormControlLabel>备注:</FormControlLabel>
    </Col>
    <Col col="10">
      <Input type="textarea" />
    </Col>
  </FormGroup>
  <FormGroup className="offset-b-lg">
    <Col col="2" className="text-right">
      <FormControlLabel>区域:</FormControlLabel>
    </Col>
    <Col col="10">
      <RadioGroup direction="column">
        <Radio>北京</Radio>
        <Radio>上海</Radio>
        <Radio>天津</Radio>
        <Radio>河北</Radio>
      </RadioGroup>
    </Col>
  </FormGroup>
  <FormGroup style={{ justifyContent: 'center' }}>
    <Button theme="primary">注册</Button>
    <Button theme="default" style={{ marginLeft: '20px' }}>
      取消
    </Button>
  </FormGroup>
</Form>
```

### 变更记录

v2.0.0

* 新增 form-group-inline-label-margin-bottom sass 变量
* 新增 form-group-inline-btn-margin-left sass 变量