<template>
  <div class="app-container">
    <el-row :gutter="32">
      <el-col :xs="24" :sm="24" :lg="6">
        <el-card class="box-card">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              物理机
            </a>
          </div>
          <el-row>
            <el-col :span="12">
              <div class="content___2qbAU">
                <div class="left___H_nrL">
                  <span class="icon___3veM-">
                    <span class="anticon zstack-icon" style="font-size: 16px;">
                      <svg width="24px" height="24px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="" style="fill: currentcolor;">
                        <g id="通用/icon-图标/物品设备/hard-drive__sStRcwWM" stroke="none" stroke-width="1" fill-rule="evenodd">
                          <path id="path-1__sStRcwWM" d="M16,15 C16.55,15 17,15.45 17,16 C17,16.55 16.55,17 16,17 L16,17 L12,17 C11.45,17 11,16.55 11,16 C11,15.45 11.45,15 12,15 L12,15 Z M8,15 C8.55,15 9,15.45 9,16 C9,16.55 8.55,17 8,17 C7.45,17 7,16.55 7,16 C7,15.45 7.45,15 8,15 Z M18,19 L6,19 C5.449,19 5,18.552 5,18 L5,13 L19,13 L19,18 C19,18.552 18.551,19 18,19 L18,19 Z M8.342,5.553 C8.512,5.212 8.855,5 9.236,5 L14.764,5 C15.145,5 15.488,5.212 15.658,5.553 L18.382,11 L5.618,11 L8.342,5.553 Z M20.789,11.342 L17.447,4.658 C16.936,3.636 15.908,3 14.764,3 L9.236,3 C8.092,3 7.064,3.636 6.553,4.658 L3.211,11.342 C3.073,11.618 3,11.928 3,12.236 L3,18 C3,19.654 4.346,21 6,21 L18,21 C19.654,21 21,19.654 21,18 L21,12.236 C21,11.928 20.927,11.618 20.789,11.342 L20.789,11.342 Z" />
                        </g>
                      </svg>
                    </span>
                  </span>
                  <span class="label___MgEcU">
                    <div class="linkCount___1h3JZ">
                      <a href="/hardware/host">1</a>
                    </div>
                    <div class="name___2-rEf">总数量</div>
                  </span>
                </div>
              </div>
            </el-col>

            <el-col :span="12">
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(87, 211, 68);" />
                <span class="zstack-state">已连接</span>
                <span class="count-state">0</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(249, 57, 64);" />
                <span class="zstack-state">未连接</span>
                <span class="count-state">1</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(150, 152, 155);" />
                <span class="zstack-state">其它</span>
                <span class="count-state">0</span>
              </div>
            </el-col>
          </el-row>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :lg="6">
        <el-card class="box-card">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              云主机
            </a>
          </div>
          <el-row>
            <el-col :span="12">
              <div class="content___2qbAU">
                <div class="left___H_nrL">
                  <span class="icon___3veM-">
                    <span class="anticon zstack-icon" style="font-size: 16px;">
                      <svg width="24px" height="24px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="" style="fill: currentcolor;"><g id="通用/icon-图标/物品设备/monitor__ru0BZULI" stroke="none" stroke-width="1" fill-rule="evenodd"><path id="path-1__ru0BZULI" d="M20,14 C20,14.551 19.552,15 19,15 L12.087,15 L11.913,15 L5,15 C4.448,15 4,14.551 4,14 L4,6 C4,5.449 4.448,5 5,5 L19,5 C19.552,5 20,5.449 20,6 L20,14 Z M19,3 L5,3 C3.346,3 2,4.346 2,6 L2,14 C2,15.654 3.346,17 5,17 L11,17 L11,19 L7,19 C6.45,19 6,19.45 6,20 C6,20.55 6.45,21 7,21 L17,21 C17.55,21 18,20.55 18,20 C18,19.45 17.55,19 17,19 L13,19 L13,17 L19,17 C20.654,17 22,15.654 22,14 L22,6 C22,4.346 20.654,3 19,3 L19,3 Z" /></g></svg>
                    </span>
                  </span>
                  <span class="label___MgEcU">
                    <div class="linkCount___1h3JZ">
                      <a href="/hardware/host">2</a>
                    </div>
                    <div class="name___2-rEf">总数量</div>
                  </span>
                </div>
              </div>
            </el-col>

            <el-col :span="12">
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(87, 211, 68);" />
                <span class="zstack-state">已连接</span>
                <span class="count-state">1</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(249, 57, 64);" />
                <span class="zstack-state">未连接</span>
                <span class="count-state">1</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(150, 152, 155);" />
                <span class="zstack-state">其它</span>
                <span class="count-state">0</span>
              </div>
            </el-col>
          </el-row>
        </el-card>
      </el-col>

      <el-col :xs="24" :sm="24" :lg="6">
        <el-card class="box-card">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              主存储
            </a>
          </div>
          <el-row>
            <el-col :span="12">
              <div class="content___2qbAU">
                <div class="left___H_nrL">
                  <span class="icon___3veM-">
                    <span class="anticon zstack-icon" style="font-size: 16px;">
                      <svg width="24px" height="24px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="" style="fill: currentcolor;"><g id="通用/icon-图标/物品设备/storage__N9segKrN" stroke="none" stroke-width="1" fill-rule="evenodd"><path id="🎨-Icon-Сolor__N9segKrN" d="M12,3 C13.3748365,3 14.677672,3.10275764 15.8431547,3.28648899 L16.371079,3.37695836 C16.8043514,3.45735369 17.2156297,3.54933082 17.6011473,3.65163422 C17.921967,3.73677384 18.2247716,3.8290041 18.5075901,3.92765472 C19.0276931,4.10907566 19.4801715,4.31219137 19.8515948,4.53252573 C19.9637573,4.59905654 20.0686709,4.66725873 20.1658,4.73691136 C20.2882134,4.82500583 20.3940278,4.91149749 20.4877669,4.99989067 C20.5658292,5.07351647 20.6353602,5.14826996 20.6961769,5.22420959 C20.7955938,5.34836765 20.8716974,5.47562742 20.922874,5.6054863 L20.9753838,5.77642103 L20.9753838,5.77642103 C20.9847711,5.82011453 20.9906894,5.85731011 20.9945574,5.8946793 L21,6 L21,18 C21,19.128071 19.1321214,20.1107198 16.371079,20.6230416 L15.8431547,20.713511 C14.677672,20.8972424 13.3748365,21 12,21 C10.6251635,21 9.32232799,20.8972424 8.15684529,20.713511 L7.62892103,20.6230416 C4.95416114,20.1267299 3.11761464,19.1890272 3.00544255,18.1053207 L3,18 L3,6 L3.00544255,5.8946793 L3.02316139,5.78310466 L3.03430802,5.73623208 L3.03430802,5.73623208 C3.08015724,5.5608119 3.1712673,5.38975367 3.30373157,5.22432387 C3.36463976,5.14826996 3.43417076,5.07351647 3.51203717,5.00007541 C3.60597219,4.91149749 3.71178658,4.82500583 3.82901552,4.74063591 C3.93132906,4.66725873 4.03624268,4.59905654 4.14856826,4.53242897 C4.51982854,4.31219137 4.97230694,4.10907566 5.4923671,3.92766966 C5.77522838,3.8290041 6.07803296,3.73677384 6.39865686,3.6516862 C6.78437033,3.54933082 7.19564861,3.45735369 7.62892103,3.37695836 L8.15684529,3.28648899 C9.23267548,3.11689082 10.42554,3.016288 11.6840379,3.00181418 L12,3 Z M12,17 C9.172374,17 6.64931326,16.5653337 4.99936997,15.8855186 L5,17.637 L5.09472732,17.7020494 C5.33698707,17.8569165 5.68767722,18.0208034 6.1276695,18.1757091 L6.35501892,18.2523302 C7.81047842,18.7219818 9.8292067,19 12,19 C14.2164727,19 16.2733543,18.7100042 17.7315055,18.2239537 C18.2725814,18.0435951 18.6899518,17.8484912 18.9520556,17.6715408 L19,17.636 L19.0016403,15.8851022 C17.3517168,16.5651562 14.8282032,17 12,17 Z M5,13.641 L5.07148086,13.6941772 C6.03776797,14.3609606 8.65010534,14.9560199 11.6635818,14.9976737 L12,15 C15.1541302,15 17.9264436,14.3856563 18.9285191,13.6941772 L19,13.641 L19.000951,7.88538629 C18.2765988,8.18387078 17.3839356,8.43510228 16.371079,8.62304164 L15.8431547,8.71351101 C14.677672,8.89724236 13.3748365,9 12,9 C10.6251635,9 9.32232799,8.89724236 8.15684529,8.71351101 L7.62892103,8.62304164 C6.61653879,8.4351903 5.72423748,8.18410611 5,7.88580568 L5,13.641 Z M12,10.9 C12.5522847,10.9 13,11.3477153 13,11.9 C13,12.4522847 12.5522847,12.9 12,12.9 C11.4477153,12.9 11,12.4522847 11,11.9 C11,11.3477153 11.4477153,10.9 12,10.9 Z M8,10.5 C8.55228475,10.5 9,10.9477153 9,11.5 C9,12.0522847 8.55228475,12.5 8,12.5 C7.44771525,12.5 7,12.0522847 7,11.5 C7,10.9477153 7.44771525,10.5 8,10.5 Z M12,5 C11.8074925,5 11.6161809,5.00218641 11.4263519,5.00649898 C11.06843,5.01463454 10.7157929,5.03033013 10.3703833,5.05317351 L9.85793247,5.09274788 L9.46558574,5.13097682 L9.46558574,5.13097682 L8.83360824,5.20798803 L8.48949688,5.25853721 L8.08123208,5.32711218 L8.08123208,5.32711218 L7.60966937,5.41906086 L7.2638027,5.49628144 L6.93766308,5.57767596 L6.62184763,5.66551469 L6.45206391,5.71687445 L6.45206391,5.71687445 L6.248,5.783 L5.98962585,5.87426363 L5.7725684,5.95896182 L5.7725684,5.95896182 L5.675,6 L5.93801161,6.10630139 L6.2684945,6.22395375 C7.72664572,6.71000415 9.78352729,7 12,7 C14.2164727,7 16.2733543,6.71000415 17.7315055,6.22395375 C17.8860986,6.17242271 18.0305933,6.11968797 18.1642535,6.06651686 L18.324,6 L18.2274316,5.95896182 C18.1337184,5.9205988 18.0344582,5.88246017 17.9299218,5.84480083 L17.712,5.77 L17.3781524,5.66551469 L17.0622734,5.577717 L16.6150878,5.46823214 L16.3896157,5.41895574 L16.0378983,5.3489999 L16.0378983,5.3489999 L15.5108412,5.2585793 L15.166632,5.20802094 C14.951733,5.17842219 14.7321899,5.1517871 14.5085951,5.12824239 L14.1702382,5.09525896 C13.8267437,5.06442327 13.4746877,5.04077726 13.116109,5.02475709 L12.4320093,5.00368131 L12.4320093,5.00368131 L12,5 Z" /></g></svg>
                    </span>
                  </span>
                  <span class="label___MgEcU">
                    <div class="linkCount___1h3JZ">
                      <a href="/hardware/host">1</a>
                    </div>
                    <div class="name___2-rEf">总数量</div>
                  </span>
                </div>
              </div>
            </el-col>

            <el-col :span="12">
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(87, 211, 68);" />
                <span class="zstack-state">已连接</span>
                <span class="count-state">1</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(249, 57, 64);" />
                <span class="zstack-state">未连接</span>
                <span class="count-state">0</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(150, 152, 155);" />
                <span class="zstack-state">其它</span>
                <span class="count-state">0</span>
              </div>
            </el-col>
          </el-row>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :lg="6">
        <el-card class="box-card">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              镜像服务器
            </a>
          </div>
          <el-row>
            <el-col :span="12">
              <div class="content___2qbAU">
                <div class="left___H_nrL">
                  <span class="icon___3veM-">
                    <span class="anticon zstack-icon" style="font-size: 16px;">
                      <svg width="24px" height="24px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="" style="fill: currentcolor;"><g id="通用/icon-图标/物品设备/server__yMajC1E2" stroke="none" stroke-width="1" fill-rule="evenodd"><path id="🎨-Icon-Сolor__yMajC1E2" d="M19,13 C20.6568542,13 22,14.3431458 22,16 L22,18 C22,19.6568542 20.6568542,21 19,21 L5,21 C3.34314575,21 2,19.6568542 2,18 L2,16 C2,14.3431458 3.34314575,13 5,13 L19,13 Z M19,15 L5,15 C4.48716416,15 4.06449284,15.3860402 4.00672773,15.8833789 L4,16 L4,18 C4,18.5128358 4.38604019,18.9355072 4.88337887,18.9932723 L5,19 L19,19 C19.5128358,19 19.9355072,18.6139598 19.9932723,18.1166211 L20,18 L20,16 C20,15.4871642 19.6139598,15.0644928 19.1166211,15.0067277 L19,15 Z M7,16 C7.55228475,16 8,16.4477153 8,17 C8,17.5522847 7.55228475,18 7,18 C6.44771525,18 6,17.5522847 6,17 C6,16.4477153 6.44771525,16 7,16 Z M11,16 C11.5522847,16 12,16.4477153 12,17 C12,17.5522847 11.5522847,18 11,18 C10.4477153,18 10,17.5522847 10,17 C10,16.4477153 10.4477153,16 11,16 Z M19,3 C20.6568542,3 22,4.34314575 22,6 L22,8 C22,9.65685425 20.6568542,11 19,11 L5,11 C3.34314575,11 2,9.65685425 2,8 L2,6 C2,4.34314575 3.34314575,3 5,3 L19,3 Z M19,5 L5,5 C4.48716416,5 4.06449284,5.38604019 4.00672773,5.88337887 L4,6 L4,8 C4,8.51283584 4.38604019,8.93550716 4.88337887,8.99327227 L5,9 L19,9 C19.5128358,9 19.9355072,8.61395981 19.9932723,8.11662113 L20,8 L20,6 C20,5.48716416 19.6139598,5.06449284 19.1166211,5.00672773 L19,5 Z M7,6 C7.55228475,6 8,6.44771525 8,7 C8,7.55228475 7.55228475,8 7,8 C6.44771525,8 6,7.55228475 6,7 C6,6.44771525 6.44771525,6 7,6 Z M11,6 C11.5522847,6 12,6.44771525 12,7 C12,7.55228475 11.5522847,8 11,8 C10.4477153,8 10,7.55228475 10,7 C10,6.44771525 10.4477153,6 11,6 Z" /></g></svg>
                    </span>
                  </span>
                  <span class="label___MgEcU">
                    <div class="linkCount___1h3JZ">
                      <a href="/hardware/host">1</a>
                    </div>
                    <div class="name___2-rEf">总数量</div>
                  </span>
                </div>
              </div>
            </el-col>

            <el-col :span="12">
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(87, 211, 68);" />
                <span class="zstack-state">已连接</span>
                <span class="count-state">0</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(249, 57, 64);" />
                <span class="zstack-state">未连接</span>
                <span class="count-state">1</span>
              </div>
              <div class="my-border" />
              <div class="state-row">
                <span class="zstack-state-prefix-dot" style="background-color: rgb(150, 152, 155);" />
                <span class="zstack-state">其它</span>
                <span class="count-state">0</span>
              </div>
            </el-col>
          </el-row>
        </el-card>
      </el-col>
    </el-row>

    <el-row :gutter="32">
      <el-col :xs="24" :sm="24" :lg="8">
        <div class="chart-wrapper">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              CPU已分配率
            </a>
          </div>
          <pie-chart />
          <div class="box">
            <div class="label">
              <b>已用：13.5%</b>
            </div>
          </div>
          <div class="box">
            <div class="label">
              <b>总量：86.5%</b>
            </div>
          </div>
        </div>
      </el-col>

      <el-col :xs="24" :sm="24" :lg="8">
        <div class="chart-wrapper">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              内存已分配率
            </a>
          </div>
          <pie-chart2 />
          <div class="box">
            <div class="label">
              <b>已用：22.50 GB</b>
            </div>
          </div>
          <div class="box">
            <div class="label">
              <b>总量：100.00 GB</b>
            </div>
          </div>
        </div>
      </el-col>

      <el-col :xs="24" :sm="24" :lg="8">
        <div class="chart-wrapper">
          <div slot="header">
            <a class="link-type link-title" target="_blank" href="https://panjiachen.github.io/vue-element-admin-site/guide/advanced/theme.html">
              主存储已分配率
            </a>
          </div>
          <pie-chart3 />
          <div class="box">
            <div class="label">
              <b>已用：70.64 GB</b>
            </div>
          </div>
          <div class="box">
            <div class="label">
              <b>总量：541.58 GB</b>
            </div>
          </div>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import path from 'path'
import PieChart from './components/PieChart'
import PieChart2 from './components/PieChart2'
import PieChart3 from './components/PieChart3'
import { deepClone } from '@/utils'
import { getRoutes, getRoles, addRole, deleteRole, updateRole } from '@/api/role'

const defaultRole = {
  key: '',
  name: '',
  description: '',
  routes: []
}

export default {
  components: {
    PieChart,
    PieChart2,
    PieChart3
  },
  data() {
    return {
      role: Object.assign({}, defaultRole),
      routes: [],
      rolesList: [],
      dialogVisible: false,
      dialogType: 'new',
      checkStrictly: false,
      defaultProps: {
        children: 'children',
        label: 'title'
      }
    }
  },
  computed: {
    routesData() {
      return this.routes
    }
  },
  created() {
    // Mock: get all routes and roles list from server
    this.getRoutes()
    this.getRoles()
  },
  methods: {
    async getRoutes() {
      const res = await getRoutes()
      this.serviceRoutes = res.data
      this.routes = this.generateRoutes(res.data)
    },
    async getRoles() {
      const res = await getRoles()
      this.rolesList = res.data
    },

    // Reshape the routes structure so that it looks the same as the sidebar
    generateRoutes(routes, basePath = '/') {
      const res = []

      for (let route of routes) {
        // skip some route
        if (route.hidden) { continue }

        const onlyOneShowingChild = this.onlyOneShowingChild(route.children, route)

        if (route.children && onlyOneShowingChild && !route.alwaysShow) {
          route = onlyOneShowingChild
        }

        const data = {
          path: path.resolve(basePath, route.path),
          title: route.meta && route.meta.title

        }

        // recursive child routes
        if (route.children) {
          data.children = this.generateRoutes(route.children, data.path)
        }
        res.push(data)
      }
      return res
    },
    generateArr(routes) {
      let data = []
      routes.forEach(route => {
        data.push(route)
        if (route.children) {
          const temp = this.generateArr(route.children)
          if (temp.length > 0) {
            data = [...data, ...temp]
          }
        }
      })
      return data
    },
    handleAddRole() {
      this.role = Object.assign({}, defaultRole)
      if (this.$refs.tree) {
        this.$refs.tree.setCheckedNodes([])
      }
      this.dialogType = 'new'
      this.dialogVisible = true
    },
    handleEdit(scope) {
      this.dialogType = 'edit'
      this.dialogVisible = true
      this.checkStrictly = true
      this.role = deepClone(scope.row)
      this.$nextTick(() => {
        const routes = this.generateRoutes(this.role.routes)
        this.$refs.tree.setCheckedNodes(this.generateArr(routes))
        // set checked state of a node not affects its father and child nodes
        this.checkStrictly = false
      })
    },
    handleDelete({ $index, row }) {
      this.$confirm('Confirm to remove the role?', 'Warning', {
        confirmButtonText: 'Confirm',
        cancelButtonText: 'Cancel',
        type: 'warning'
      })
        .then(async() => {
          await deleteRole(row.key)
          this.rolesList.splice($index, 1)
          this.$message({
            type: 'success',
            message: 'Delete succed!'
          })
        })
        .catch(err => { console.error(err) })
    },
    generateTree(routes, basePath = '/', checkedKeys) {
      const res = []

      for (const route of routes) {
        const routePath = path.resolve(basePath, route.path)

        // recursive child routes
        if (route.children) {
          route.children = this.generateTree(route.children, routePath, checkedKeys)
        }

        if (checkedKeys.includes(routePath) || (route.children && route.children.length >= 1)) {
          res.push(route)
        }
      }
      return res
    },
    async confirmRole() {
      const isEdit = this.dialogType === 'edit'

      const checkedKeys = this.$refs.tree.getCheckedKeys()
      this.role.routes = this.generateTree(deepClone(this.serviceRoutes), '/', checkedKeys)

      if (isEdit) {
        await updateRole(this.role.key, this.role)
        for (let index = 0; index < this.rolesList.length; index++) {
          if (this.rolesList[index].key === this.role.key) {
            this.rolesList.splice(index, 1, Object.assign({}, this.role))
            break
          }
        }
      } else {
        const { data } = await addRole(this.role)
        this.role.key = data.key
        this.rolesList.push(this.role)
      }

      const { description, key, name } = this.role
      this.dialogVisible = false
      this.$notify({
        title: 'Success',
        dangerouslyUseHTMLString: true,
        message: `
            <div>Role Key: ${key}</div>
            <div>Role Name: ${name}</div>
            <div>Description: ${description}</div>
          `,
        type: 'success'
      })
    },
    // reference: src/view/layout/components/Sidebar/SidebarItem.vue
    onlyOneShowingChild(children = [], parent) {
      let onlyOneChild = null
      const showingChildren = children.filter(item => !item.hidden)

      // When there is only one child route, the child route is displayed by default
      if (showingChildren.length === 1) {
        onlyOneChild = showingChildren[0]
        onlyOneChild.path = path.resolve(parent.path, onlyOneChild.path)
        return onlyOneChild
      }

      // Show parent if there are no child route to display
      if (showingChildren.length === 0) {
        onlyOneChild = { ... parent, path: '', noShowingChildren: true }
        return onlyOneChild
      }

      return false
    }
  }
}
</script>

<style lang="scss" scoped>
.app-container {
  background-color: rgb(240, 242, 245);
  .roles-table {
    margin-top: 30px;
  }
  .permission-tree {
    margin-bottom: 30px;
  }
}
.box-card {
  width: 400px;
  max-width: 100%;
  margin: 20px 5px;
}
.chart-wrapper {
  background: #fff;
  padding: 16px 16px 0;
  margin-bottom: 32px;
}

.box{
  display: flex;
  flex-direction: row;
  flex-flow: nowrap;
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 8px;
  font-size: 14px;
  color: var(--neutral-600);
  width: 100%;
}
.label{
  width: 33%;
  margin-left: 200px;
  margin-right: 4px;
  //align: center;
  margin-bottom: 4px;
  white-space: nowrap;
  overflow: hidden;
}

.state-row{
  width: 100%;
  padding: 0 4px;
  font-size: 14px;
  color: #707275;
  white-space: nowrap;
  overflow: hidden;
  //height: 40px;
  //line-height: 40px;

}

.my-border{
  border-bottom: 1px solid #DBDDE0;
  margin-top: 10px;
  margin-bottom: 10px;
}

.zstack-state {
  padding: 0 6px;
  display: inline-flex;
  align-items: center;
  vertical-align: middle;
}
.count-state{
  float: right;
  color: #4A4C4F;
}

.zstack-state-prefix-dot {
  display: inline-block;
  width: 8px;
  height: 8px;
  border-radius: 50%;
}

.content___2qbAU {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

.left___H_nrL {
  //width: 50%;
  text-align: center;
  padding-top: 20px;
  margin:auto auto;
}

.anticon {
  display: inline-block;
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -0.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.zstack-icon {
  background: #F5F7FA;
  padding: 14px;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  color: #707275
}

.icon___3veM- {
  display: inline-block;
}

.name___2-rEf {
  font-size: 14px;
  color: #707275
}

.label___MgEcU {
  display: inline-block;
  margin-left: 10px;
  vertical-align: top;
  line-height: 30px;
}

.linkCount___1h3JZ {
  font-size: 24px;
  color: #181A1D;
  cursor: pointer;
}
</style>
