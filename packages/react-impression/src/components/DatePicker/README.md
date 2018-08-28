### 示例

**基本用法**

```js
<Row>
  <Col>
    <Form>
      <FormGroup>
        <label>默认:</label>
        <Input type="date" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>默认值（非受控组件）:</label>
        <Input type="date" defaultValue="2016-05-29" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>禁用状态:</label>
        <Input type="date" defaultValue="2016-05-29" disabled />
      </FormGroup>
    </Form>
  </Col>
</Row>
```

**限制日期**

```js
<Row>
  <Col>
    <Form>
      <FormGroup>
        <label>最小值:</label>
        <Input type="date" defaultValue="2016-05-29" minDate="2016-05-15" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>最大值:</label>
        <Input type="date" defaultValue="2016-05-29" maxDate="2016-05-31" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>设置每周第一天是星期几:</label>
        <Input type="date" defaultValue="2016-05-29" firstDayOfWeek={1} />
      </FormGroup>
    </Form>
  </Col>
</Row>
```

**格式化**

```js
<Row>
  <Col>
    <Form>
      <FormGroup>
        <label>年-月-日:</label>
        <Input type="date" defaultValue="2016-5-29" format="Y-M-D" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>年/月月/日日:</label>
        <Input type="date" defaultValue="2016/05/29" format="YYYY/MM/DD" />
      </FormGroup>
    </Form>
  </Col>
  <Col>
    <Form>
      <FormGroup>
        <label>年月日:</label>
        <Input
          type="date"
          defaultValue="2016年05月29日"
          format="YYYY年MM月DD日"
        />
      </FormGroup>
    </Form>
  </Col>
</Row>
```

**月份选择**

```js
<Row>
  <Col>
    <Form>
      <FormGroup>
        <label>年月:</label>
        <Input type="month" />
      </FormGroup>
    </Form>
  </Col>
</Row>
```