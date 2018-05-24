<template>
    <div>
        <div class="crumbs">
            <el-breadcrumb separator="/">
                <el-breadcrumb-item><i class="el-icon-date"></i> 组件开发</el-breadcrumb-item>
                <el-breadcrumb-item>组件列表</el-breadcrumb-item>
            </el-breadcrumb>
        </div>
        <div class="container">
             <el-tabs v-model="message">
                <el-tab-pane label="首页" name="first">
                     <el-col :span="24">
                        <el-row>
                            <el-col>
                                 <el-card shadow="hover">
                                    <div slot="header" class="clearfix">
                                        <span>首页的</span>
                                    </div>
                                    Vue
                                  
                                </el-card>
                            </el-col>
                        </el-row>
                     </el-col>
                </el-tab-pane>
                <el-tab-pane label="列表页" name="second">
                     <el-col :span="24">
                        <el-row>
                            <el-col>
                                 <el-card shadow="hover">
                                    <div slot="header" class="clearfix">
                                        <span>首页浓缩列表</span>
                                    </div>
                                   
                                </el-card>
                            </el-col>
                        </el-row>
                     </el-col>
                </el-tab-pane>
                <el-tab-pane label="详情页" name="three">
                     <el-col :span="24">
                        <el-row>
                            <el-col>
                                 <el-card shadow="hover">
                                    <div slot="header" class="clearfix">
                                        <span>详情页</span>
                                    </div>
                                 
                                </el-card>
                            </el-col>
                        </el-row>
                     </el-col>
                </el-tab-pane>
                <el-tab-pane label="单页" name="four">
                     <el-col :span="24">
                        <el-row>
                            <el-col>
                                 <el-card shadow="hover">
                                    <div slot="header" class="clearfix">
                                        <span>单页面</span>
                                    </div>
                                   
                                </el-card>
                            </el-col>
                        </el-row>
                     </el-col>
                </el-tab-pane>
                <el-tab-pane label="留言页" name="five">
                     <el-col :span="24">
                        <el-row>
                            <el-col>
                                 <el-card shadow="hover">
                                    <div slot="header" class="clearfix">
                                        <span>留言</span>
                                    </div>
                                   
                                </el-card>
                            </el-col>
                        </el-row>
                     </el-col>
                </el-tab-pane>
             </el-tabs>
        </div>
     
    </div>
</template>

<script>
    
    export default {
        data(){
            return {
                content:'',
                html:'',
                configs: {
                },
                message: 'first'
            }
        }
    }
</script>
<style scoped>
    .editor-btn{
        margin-top: 20px;
    }
</style>