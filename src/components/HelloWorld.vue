<script setup>
  import { Input,Button, Form, Col, Row, Switch, Select, } from "@kousum/semi-ui-vue"
  import { IconMinusCircleStroked  } from '@kousum/semi-icons-vue'

</script>

<template>
  <Row>
    <h1>Create DataTable</h1>
  </Row>
  <Row> 
    <h3>Table Name</h3>
    <Input style="width: 100%" />
  </Row>  
  <Row style="padding-top: 2rem;padding-bottom: 1rem">
    <span style="margin-right: 2rem;">Fileds</span>
    <Button type="primary">Add Fileds</Button>
  </Row>

  <Row style="background-color: rgba(var(--semi-grey-8), .05); padding-bottom: 1rem;">
    <Col span="2" className="col-contentz">
    <div style="position: relative">
      <IconMinusCircleStroked style="color: #E91E63; position: absolute; left: 50%; top: 90px" size="extra-large"/>
    </div>
    </Col>
    <Col span="22" className="col-content">
      <Row>
      <Col span="8" className="col-content">
        <div>
          <h3>Name</h3>
          <Input placeholder="id" style="width: 30rem;"/>
        </div>        
      </Col>
      <Col span="8" className="col-content">
        <div>
          <h3>Type</h3>
          <Select placeholder="Auto Create ID" style="width: 30rem;">

          </Select>
        </div>
      </Col>
    </Row>
        <Col span="8" className="col-content">
        <div>
          <h3>Description</h3>
          <Input placeholder="Auto Create ID" style="width: 30rem;"/>
        </div>
        </Col>
        <Col span="8" className="col-content">
        <div>
          <h3>Default</h3>
          <Input style="width: 30rem;"/>
        </div>
      </Col>
      <Col span="8" className="col-content">
        <Col span="12" className="col-content">
            <h3>Unique</h3>
            <Switch></Switch>
        </Col>
          <Col span="12" className="col-content">
            <h3>Required</h3>
            <Switch></Switch>
          </Col>
      </Col>  
      </Col>
    </Row>
      <Row style="background-color: rgba(var(--semi-grey-8), .09); padding-bottom: 1rem">
    <Col span="2" className="col-content">
    <div style="position: relative;">
      <IconMinusCircleStroked style="color: #E91E63; position: absolute; left: 50%; top: 90px" size="extra-large"/>
    </div>
    </Col>
    <Col span="22" className="col-content">
      <Row>
      <Col span="8" className="col-content">
        <div>
          <h3>Name</h3>
          <Input placeholder="id" style="width: 30rem;"/>
        </div>        
      </Col>
      <Col span="8" className="col-content">
        <div>
          <h3>Type</h3>
          <Select defaultValue="Auto Create ID" style="width: 30rem;">
          </Select>
        </div>
      </Col>
    </Row>
        <Col span="8" className="col-content">
        <div>
          <h3>Description</h3>
          <Input placeholder="Auto Create ID" style="width: 30rem;"/>
        </div>
        </Col>
        <Col span="8" className="col-content">
        <div>
          <h3>Default</h3>
          <Input style="width: 30rem;"/>
        </div>
      </Col>
      <Col span="8" className="col-content">
        <Col span="12" className="col-content">
            <h3>Unique</h3>
            <Switch></Switch>
        </Col>
          <Col span="12" className="col-content">
            <h3>Required</h3>
            <Switch></Switch>
          </Col>
      </Col>  
      </Col>
    </Row> 
  <Row style="background-color: rgba(var(--semi-grey-8), .05); padding-bottom: 1rem; margin-bottom: 1rem;" >
    <Col span="2" className="col-content">
    <div style="position: relative;">
      <IconMinusCircleStroked style="color: #E91E63; position: absolute; left: 50%; top: 90px" size="extra-large"/>
    </div>
    </Col>
    <Col span="22" className="col-content">
      <Row>
      <Col span="8" className="col-content">
        <div>
          <h3>Name</h3>
          <Input placeholder="id" style="width: 30rem;"/>
        </div>        
      </Col>
      <Col span="8" className="col-content">
        <div>
          <h3>Type</h3>
          <Select defaultValue="Auto Create ID" style="width: 30rem;">
          </Select>
        </div>
      </Col>
    </Row>
        <Col span="8" className="col-content">
        <div>
          <h3>Description</h3>
          <Input placeholder="Auto Create ID" style="width: 30rem;"/>
        </div>
        </Col>
        <Col span="8" className="col-content">
        <div>
          <h3>Default</h3>
          <Input style="width: 30rem;"/>
        </div>
      </Col>
      <Col span="8" className="col-content">
        <Col span="12" className="col-content">
            <h3>Unique</h3>
            <Switch></Switch>
        </Col>
          <Col span="12" className="col-content">
            <h3>Required</h3>
            <Switch></Switch>
          </Col>
      </Col>  
      </Col>
    </Row>
    <Button style="margin-right:1rem;">Submit</Button> 
    <Button>Cancel</Button>


</template>

<style scoped>
</style>
