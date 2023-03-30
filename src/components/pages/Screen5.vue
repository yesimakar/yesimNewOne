<template>
  <DropZone ncBgType="bgImage"
    backgroundImage="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/NewTux.svg/1707px-NewTux.svg.png"
    background="" id="f205f7cd-19ef-48fe-9131-10c8a311235c" v-bind:style="{'width':'100%','height':'auto'}">
    <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
      color="#FFFFFF" theme="theme--light01" v-bind:squared="false" variant="primary" ncBgType="bgColor"
      v-bind:isEnabled="true" background="#007bff" linkTarget="_top" ncLinkType="link" borderColor="#007bff"
      ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
      horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
      nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
      ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
      ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
      position="relative" id="0ea84d39-1f3a-4867-85dd-191ad3be881c"
      v-bind:style="{'width':'100%','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':2}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen5',
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
@media (min-width: 1024.05px){[id='f205f7cd-19ef-48fe-9131-10c8a311235c'] {
             display: grid; 
             grid-template-columns: 14.5703125rem 5.3125rem 80.1171875rem;
             grid-template-rows: minmax(21.171875rem, max-content) minmax(2.421875rem, max-content) minmax(64.84375rem, max-content);
          }
[id='0ea84d39-1f3a-4867-85dd-191ad3be881c']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='f205f7cd-19ef-48fe-9131-10c8a311235c'] {
             display: grid; 
             grid-template-columns: 46.6796875rem 6.640625rem 46.6796875rem;
             grid-template-rows: minmax(26.46484375rem, max-content) minmax(3.02734375rem, max-content) minmax(3.125rem, max-content);
          }
[id='0ea84d39-1f3a-4867-85dd-191ad3be881c']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='f205f7cd-19ef-48fe-9131-10c8a311235c'] {
             display: grid; 
             grid-template-columns: 45.572916666666664rem 8.854166666666666rem 45.572916666666664rem;
             grid-template-rows: minmax(35.286458333333336rem, max-content) minmax(4.036458333333333rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='0ea84d39-1f3a-4867-85dd-191ad3be881c']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='f205f7cd-19ef-48fe-9131-10c8a311235c'] {
             display: grid; 
             grid-template-columns: 42.916666666666664rem 14.166666666666666rem 42.916666666666664rem;
             grid-template-rows: minmax(56.458333333333336rem, max-content) minmax(6.458333333333333rem, max-content) minmax(5rem, max-content);
          }
[id='0ea84d39-1f3a-4867-85dd-191ad3be881c']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),2.5rem);
          
          }}

@media (min-width: 0px) and (max-width: 375px){[id='f205f7cd-19ef-48fe-9131-10c8a311235c'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.20000000000002rem 6.4rem;
             grid-template-rows: minmax(72.26666666666667rem, max-content) minmax(39.7529411764706rem, max-content) minmax(6.4rem, max-content);
          }
[id='0ea84d39-1f3a-4867-85dd-191ad3be881c']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),15.38823529411765rem);
          
          }}
</style>