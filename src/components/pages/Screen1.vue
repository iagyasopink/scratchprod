<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="525"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="cd761c08-958c-481f-a409-a10ed61928f5" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <MultipleState v-bind:fade="true" v-bind:isLock="false" bgColor=""
        v-bind:tabRawData="{'20001124144305863u9BeGxKvUBzsPbOFQDz':{'name':'State 1','children':[]}}"
        currentIndex="20001124144305863u9BeGxKvUBzsPbOFQDz" ncTooltipText="" v-bind:tabVisibility="true"
        position="absolute" top="37.453978159126365%" left="34.54347826086956%"
        id="ee39c1a2-d874-4ea6-ba50-278d38c73625"
        v-bind:style="{'color':'#FFFFFF','width':'295.575','height':'168.89999999999998','maxWidth':'','minWidth':'','tabIndex':'-0.563','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','background':'','marginLeft':'0px','paddingTop':'','visibility':'visible','borderColor':'#dee2e6','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.563px','borderLeftWidth':'0.563px','borderRightWidth':'0.563px','borderBottomWidth':'0.563px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
      <WAdvertisement v-bind:blank="true" imgSrc="" v-bind:overlay="true" cardText="Medium Rectangle" imgWidth="300px"
        bgVariant="secondary" imgHeight="300px" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        verticalPosition="align-items-center" horizontalPosition="justify-content-center" position="absolute"
        top="15.62402496099844%" left="36.57065217391305%" id="a2e364e3-ecff-47b5-ace7-5bea9aba1e33"
        v-bind:style="{'width':'197.04999999999998','height':'33.779999999999994','maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':3}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>