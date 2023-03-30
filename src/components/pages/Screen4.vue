<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="2e8fa363-2e60-4f83-989c-ded862ff4f6a"
    v-bind:style="{'width':'100%','height':'auto','background':'#81A651FF'}">
    <WRoundedImage v-bind:blank="false" v-bind:rounded="true" stretch="none"
      imageUrl="https://picsum.photos/500/250/?image=84" v-bind:isEnabled="true" v-bind:thumbnail="false"
      blankColor="black" v-bind:aspectRatio="true" dataLoading="static"
      ncTooltipText="Please write a text to display in tooltip..."
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
      ncClickBorderColor="black" ncHoverBorderColor="black" dataModelForDynamicType="string" position="relative"
      v-bind:snapX="false" v-bind:snapY="false" id="3f8763b4-57b0-4ca2-9813-26e049579559"
      v-bind:style="{'width':'100%','height':'100%','boxShadow':'','marginTop':'0px','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen4',
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

<style lang="scss" scoped>
@media (min-width: 1024.05px){[id='2e8fa363-2e60-4f83-989c-ded862ff4f6a'] {
             display: grid; 
             grid-template-columns: 27.890625rem 39.0625rem 33.046875rem;
             grid-template-rows: minmax(29.0625rem, max-content) minmax(19.53125rem, max-content) minmax(62.34375rem, max-content);
          }
[id='3f8763b4-57b0-4ca2-9813-26e049579559']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 2;
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='2e8fa363-2e60-4f83-989c-ded862ff4f6a'] {
             display: grid; 
             grid-template-columns: 25.5859375rem 48.828125rem 25.5859375rem;
             grid-template-rows: minmax(36.328125rem, max-content) minmax(24.4140625rem, max-content) minmax(3.125rem, max-content);
          }
[id='3f8763b4-57b0-4ca2-9813-26e049579559']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 2;
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='2e8fa363-2e60-4f83-989c-ded862ff4f6a'] {
             display: grid; 
             grid-template-columns: 4.166666667000001rem 91.666666666rem 4.166666667000001rem;
             grid-template-rows: minmax(48.4375rem, max-content) minmax(45.833333333rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='3f8763b4-57b0-4ca2-9813-26e049579559']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 2;
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='2e8fa363-2e60-4f83-989c-ded862ff4f6a'] {
             display: grid; 
             grid-template-columns: 5rem 90rem 5rem;
             grid-template-rows: minmax(77.5rem, max-content) minmax(45rem, max-content) minmax(5rem, max-content);
          }
[id='3f8763b4-57b0-4ca2-9813-26e049579559']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 2;
          }}

@media (min-width: 0px) and (max-width: 375px){[id='2e8fa363-2e60-4f83-989c-ded862ff4f6a'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: minmax(99.2rem, max-content) minmax(43.6rem, max-content) minmax(6.4rem, max-content);
          }
[id='3f8763b4-57b0-4ca2-9813-26e049579559']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 2;
          }}
</style>