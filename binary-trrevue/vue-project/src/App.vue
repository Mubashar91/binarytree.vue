<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>


<template>
  <div style="background-color: #e8f0fe; width: auto">
    <div
      class="draggable"
      :style="{ left: `${position.x}px`, top: `${position.y}px` }"
      @mousedown="startDrag"
    >
      <div class="content">
        <div>
          <div class="container-fuild tree">
            <div class="row rowset">
              <div style="margin-left: 670px">
                <!-- card -->
                <div class="card node node1">
                  <!-- top border image -->
                  <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                  <!-- body -->
                  <div style="text-align: center" class="card-body">
                    <!-- togggle tip -->
                    <div class="ellipsis-container">
                      <i class="fa-solid fa-ellipsis-vertical"></i>
                      <span class="tooltip-text">Tooltip Text</span>
                    </div>
                    <!-- name -->
                    <div class="namestyle">John smith</div>

                    <!-- icons div -->
                    <div class="me">
                      <div class="nodedata align-self-center w-50 me1">
                        <div>
                          <i class="fa-solid fa-star"></i>
                          <i class="fa-solid fa-question"></i>
                        </div>
                      </div>
                      <div class="nodedata align-self-center w-50 me2">
                        <div style="height: auto">
                          <div>
                            <i class="fa-solid fa-fire">fk</i>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div>
                <div class="card node node1">
                  <!-- top border image -->
                  <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                  <!-- body -->
                  <div style="text-align: center" class="card-body">
                    <!-- togggle tip -->
                    <div class="ellipsis-container">
                      <i class="fa-solid fa-ellipsis-vertical"></i>
                      <span class="tooltip-text">Tooltip Text</span>
                    </div>
                    <!-- name -->
                    <div class="namestyle">John smith</div>

                    <!-- icons div -->
                    <div class="me">
                      <div class="nodedata align-self-center w-50 me1">
                        <div>
                          <i class="fa-solid fa-star"></i>
                          <i class="fa-solid fa-question"></i>
                        </div>
                      </div>
                      <div class="nodedata align-self-center w-50 me2">
                        <div style="height: auto">
                          <div>
                            <i class="fa-solid fa-fire">fk</i>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- Horizontal Connector -->
            <div class="connector-horizontal"></div>
            <!-- Vertical Connector to Child Nodes -->
            <div class="connector-vertical"></div>
            <!-- Child Nodes -->

            <div class="row rowset">
              <div style="margin-left: 540px">
                <div class="card node node1">
                  <!-- top border image -->
                  <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                  <!-- body -->
                  <div style="text-align: center" class="card-body">
                    <!-- togggle tip -->
                    <div class="ellipsis-container">
                      <i class="fa-solid fa-ellipsis-vertical"></i>
                      <span class="tooltip-text">Tooltip Text</span>
                    </div>
                    <!-- name -->
                    <div class="namestyle">John smith</div>

                    <!-- icons div -->
                    <div class="me">
                      <div class="nodedata align-self-center w-50 me1">
                        <div>
                          <i class="fa-solid fa-star"></i>
                          <i class="fa-solid fa-question"></i>
                        </div>
                      </div>
                      <div class="nodedata align-self-center w-50 me2">
                        <div style="height: auto">
                          <div>
                            <i class="fa-solid fa-fire">fk</i>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div>
                <div class="card node node1">
                  <!-- top border image -->
                  <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                  <!-- body -->
                  <div style="text-align: center" class="card-body">
                    <!-- togggle tip -->
                    <div class="ellipsis-container">
                      <i class="fa-solid fa-ellipsis-vertical"></i>
                      <span class="tooltip-text">Tooltip Text</span>
                    </div>
                    <!-- name -->
                    <div class="namestyle">John smith</div>

                    <!-- icons div -->
                    <div class="me">
                      <div class="nodedata align-self-center w-50 me1">
                        <div>
                          <i class="fa-solid fa-star"></i>
                          <i class="fa-solid fa-question"></i>
                        </div>
                      </div>
                      <div class="nodedata align-self-center w-50 me2">
                        <div style="height: auto">
                          <div>
                            <i class="fa-solid fa-fire">fk</i>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Horizontal Connector -->
          <div style="margin-left: -130px" class="connector-horizontal"></div>
          <!-- Vertical Connector to Grandchild Nodes -->
          <div style="margin-right:175px" class="connector-vertical"></div>
          <!-- Grandchild Nodes -->

          <div class="row rowset">
            <div style="margin-left: 410px">
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Horizontal Connector -->
          <div style="margin-left: -260px" class="connector-horizontal"></div>
          <!-- Vertical Connector to New Child Nodes -->
          <div style="margin-right:350px" class="connector-vertical"></div>
          <!-- New Child Nodes -->

          <div class="row rowset">
            <div style="margin-left: 280px">
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Horizontal Connector for New Child Nodes -->
          <div style="margin-left: -390px" class="connector-horizontal"></div>
          <!-- Vertical Connector to New Child Nodes at the bottom -->
          <div style="margin-right:525px" class="connector-vertical"></div>
          <!-- New Bottom Child Nodes -->

          <div class="row rowset">
            <div style="margin-left: 150px">
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="card node node1">
                <!-- top border image -->
                <img src="/12345.jpg" alt="Parent 1" class="preimg" />
                <!-- body -->
                <div style="text-align: center" class="card-body">
                  <!-- togggle tip -->
                  <div class="ellipsis-container">
                    <i class="fa-solid fa-ellipsis-vertical"></i>
                    <span class="tooltip-text">Tooltip Text</span>
                  </div>
                  <!-- name -->
                  <div class="namestyle">John smith</div>

                  <!-- icons div -->
                  <div class="me">
                    <div class="nodedata align-self-center w-50 me1">
                      <div>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-question"></i>
                      </div>
                    </div>
                    <div class="nodedata align-self-center w-50 me2 namestyle1">
                      <div style="height: auto">
                        <div>
                          <i class="fa-solid fa-fire">fk</i>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Horizontal Connector for Bottom Child Nodes -->
          <div style="margin-left: -520px" class="connector-horizontal"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
$(document).ready(function () {
  $('.node').on('click', function () {
    // Remove 'active' class from all nodes
    $('.node').removeClass('active')
    // Add 'active' class to the clicked node
    $(this).addClass('active')
  })
})

export default {
  props: {
    content: String,
    initialPosition: {
      type: Object,
      default: () => ({ x: 0, y: 0 })
    }
  },
  data() {
    return {
      position: { ...this.initialPosition },
      dragging: false,
      offset: { x: 0, y: 0 }
    }
  },
  methods: {
    startDrag(event) {
      this.dragging = true
      this.offset.x = event.clientX - this.position.x
      this.offset.y = event.clientY - this.position.y
      document.addEventListener('mousemove', this.onDrag)
      document.addEventListener('mouseup', this.stopDrag)
    },
    onDrag(event) {
      if (this.dragging) {
        this.position.x = event.clientX - this.offset.x
        this.position.y = event.clientY - this.offset.y
      }
    },
    stopDrag() {
      this.dragging = false
      document.removeEventListener('mousemove', this.onDrag)
      document.removeEventListener('mouseup', this.stopDrag)
    }
  }
}
</script>




<style scoped>
.draggable {
  position: absolute;

  padding: 10px;
  cursor: grab;
}
.draggable:active {
  cursor: grabbing;
}

.tree {
  display: flex;
  justify-content: right !important;

  flex-direction: column;
  margin-top: 60px;
  margin-left: 0px !important;
  margin-right: 0px !important;

  width: 100% !important;
}

.node {
  background-color: white;
  height: auto;
  width: 160px;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: white;
  border: 2px solid transparent;
  /* Default border */
  transition: border-color 0.3s;
  /* Smooth transition for border color */
}

.me {
  display: flex;
  padding-left: 26px;
  padding-right: 20px;
}

.me1 {
  height: auto;
  color: gray;
  object-fit: cover;
}

.me2 {
  margin-left: 15% !important;
  margin-right: 2%;
  color: gray;
  height: auto;
}

.node.active {
  border-color: yellow;
  /* Border color when active */
  box-shadow: 0 0 10px rgba(255, 255, 0, 0.5);
  /* Optional shadow effect */

}

.preimg {
  position: absolute;
  top: -30px;
  left: 50%;
  transform: translateX(-50%);
  width: 80px !important;
  height: 80px !important;
  margin-top: -30px;
}

.card-body {
  margin-top: 55px;
}

.node img {
  position: absolute;
  top: 0;
  width: 50px;
  /* Adjust size as needed */
  height: 50px;
  /* Adjust size as needed */
}

.connector-horizontal {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
  position: relative;
  margin-top: -100px;
}

.connector-horizontal::before {
  content: '';
  position: absolute;
  left: 24.3%;
  width: 8%;
  height: 1px;
  background-color: #857f7f;
  margin-top: -70px;
  position: relative;
  margin-left: 5px;
}

.connector-horizontal-long {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
}

.connector-horizontal-long::before {
  content: '';
  position: absolute;
  left: 51%;
  width: 27px;
  height: 1px;
  background-color: #857f7f;
  margin-top: -50px;
  margin-left: 55px;
}

.connector-horizontal-long1 {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: center;
}

.connector-horizontal-long1::before {
  content: '';
  position: absolute;
  left: 33%;
  width: 18%;
  height: 1px;
  background-color: #857f7f;
  margin-top: -50px;
  margin-left: 75px;
}

.connector-vertical {
  position: relative;
  height: 40px;
  display: flex;
  justify-content: center;
}

.connector-vertical::before {
  content: '';
  position: absolute;
  top: 0;
  left: 74.5%;
  width: 1px;
  height: 250px;
  background-color: #857f7f;
  margin-top: -70px;
}

.connector-vertical-long {
  position: relative;
  height: 40px;
  display: flex;
  justify-content: center;
}

.connector-vertical-long::before {
  content: '';
  position: absolute;
  top: 0;
  width: 1px;
  height: 160px;
  background-color: #857f7f;
  margin-top: -70px;
}

.namestyle {
  width: 132px;
  height: auto;
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 38px;
  margin-bottom: 20px;
}

.namestyle1 {
  
  height: auto;

}

.nodedata {
  background-color: #f2f3f8;

  border-radius: 6px;
}

.node1 {
  position: relative;
  text-align: center;
  margin-right: 100px;
}

.ellipsis-container {
  position: relative;
  margin-left: 140px;
  margin-top: -70px;
  border-radius: 50px;
  background-color: none;
  height: 25px;
  width: 25px;
  font-size: 10px;
  text-align: center;
  padding-top: 5px;
  position: relative;
}

.ellipsis-container:hover {
  background-color: black;
  color: white;
}

.ellipsis-container:hover .fa-ellipsis-vertical {
  color: white;
}

.tooltip-text {
  visibility: hidden;
  width: 100px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px 0;
  position: absolute;
  bottom: -35px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 1;
  font-size: 10px;
}

.ellipsis-container:hover .tooltip-text {
  visibility: visible;
}
.rowset {
  margin-bottom: 8%;
  margin-top: 7%;
}
</style>